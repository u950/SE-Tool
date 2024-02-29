# SE-Tool
to develop a tool for SE course : JAVA codebase visulization

# implementation
JGIT : interacting with git repo <br>
parsing library : ANTLR or JavaCC parsing Java Source code <br>
visualization library : D3.js

Back end :
	programming language : Java JS
	web frame work : node js
	Git intaction : JGIT
	Code parsing : ANTlR OR javacc

Front ENd :
	HTML ,CSS, REACT
	Node link VISUALIZATION ; D3.js or Cytoscape.js for 


Develoment process :
	@ BACK end:
		# Implement API end points  server side
		% Fuctionalities like :
			* clone or access git repo
			* parse code base using libraries
			* Extract info about classes, methods and their relations 
			* prepare data for front end visulaization 

	 @ Front end:
		# Design UI for input user data  to input Git Repo 
			% implment logic to :
				* Fetch data from backend ApI on user i
				*  utilizing visulization library to render node-link diagram 
				* Features like Zoom, pannig , filter 
		$ integrate front end and backend 

Things to consider :
	* fetchind git repo data 
	* Core logic :  Parsing code javaCC
			     :	preparing data for visualization , 
			     : 	core feture from "D3.JS " library . imp for node link diagram genration 
 			     => generating the disgram from the libraryD3
