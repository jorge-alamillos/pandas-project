 #### PANDAS-PROJECT ####

1. OBJECTIVE

The objective of the project consists of the validation of two hypotheses raised from the Attacks.csv dataset (see source), which contains a record of shark attacks around the world.
The hypotheses to be validated are the following:
    A.- Australia is the country that suffered the most shark attacks and deaths since 1900 by    cosatline length.
    B.-  Surfing is the sport in which the most shark attacks have been recorded since 1900 in the USA and Australia.



2. SOURCE
Attacks.csv: https://www.kaggle.com/teajay/global-shark-attacks?select=attacks.csv

3. TAILORED PROCEDURES:

Treatment of the dataset is carried out before a conclusion can be drawn. After this, the analysis of the data obtained leads to the validation of the hypotheses.

See a breakdown of the work done by executing the file 'Shark_validation.ipynb' inside 'Output' folder of this repository.

4. CONCLUSION


A.- HYPOTHESIS REFUTED: The country that suffered the most shark attacks, and deaths, per kilometer of coastline since 1900 is South Africa. 



 	Country	Coastline_Km	Attack_Cases	Death_Cases	Attacks_by_1000km	  Deaths_by_1000km
	SOUTH AFRICA	   2798	    282            48               100.786276	       17.155111
	USA	          19924	   1141	    65	             57.267617         	3.262397
       AUSTRALIA	   25148	    608	   107               24.176873	        4.254812
	BRAZIL	           7491             76            26               10.145508    	        3.470832
	PAPUA NEW GUINEA   5152	     51	    23	              9.899068	                4.464286

B.- HYPOTHESIS NOT REFUTED: Surfing is the sport in which the most shark attacks have been recorded since 1900 in the USA and Australia.

                                                        	ATTACKS IN USA   %
                                                Activity	
                                                Surfing	    562	56.8
                                                Swimming	    285	28.8
                                                Fishing	    100	10.1
                                                Divin             26	        2.6
                                                Swimming	    15  	1.51

                                                       ATTACKS IN AUSTRALIA    %
                                                Activity	
                                                Surfing	    195	42.1
                                                Swimming	    133	28.7
                                                Fishing	     97	20.9
                                                Diving	     28	 6.0
                                                Swimming	     10	 2.1


