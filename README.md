# README
This is a Python based application that takes in historical weather data from winter 2017/2018 and elevation data taken by NASA's Shuttle Radar Topgraphy Misson (SRTM). The program then creates a risk analysis of any region in the greater Salt Lake City area on any date in the winter season. It contains a command line GUI for the user to imput the name of the area along with four latitude and longitude bounds and outputs a interactive 2D and 3D map for the user to see where the safest area is to ski. 

The engine of this program is broken up into three seperate parts. Part one works on taking elevation data given from the SRTM and finding the specific angle of every 40 meter section of the region. Part two creates a snowpack model, an eveluation of each layer of snow, by using the Scipy ordinary diffrental equations module in addition with all the the weather data for all days starting from the begining of the season. The third part of this engine cross referances the snowpack model with the specific angle at each point. This part then adds an extra stress variable for a skiier going down the face of the region. From this data the specific risk of an avalanche from a skier can be found.

Updates for this program will be coming. These updates will include global historical data so the program can be run anywhere with out limitations. In addition a gradent risk anylysis will be implimented for better user experience.


This repository contains my projetcs. These projects are under exclusive copyright: © 2018 Patrick Schulz. All rights reserved.
