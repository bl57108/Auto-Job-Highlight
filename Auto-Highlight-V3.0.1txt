@echo off
set Output="%USERPROFILE%\desktop"
TITLE BJ Auto Highlight V3.0

REM set the doc first and last name
		set /p DocFirst=Enter Doctor First Name:
		set /p DocLast=Enter Doctor Last Name:



REM set default license values to on
		set AlabamaN=Alabama								
		set AlaskaN=Alaska
		set ArkansasN=Arkansas
		set ArizonaN=Arizona
		set CaliforniaN=California
		set ColoradoN=Colorado
		set ConnecticutN=Connecticut
		set DelawareN=Delaware
		set FloridaN=Florida
		set GeorgiaN=Georgia
		set HawaiiN=Hawaii
		set IowaN=Iowa
		set IdahoN=Idaho
		set IllinoisN=Illinois
		set IndianaN=Indiana
		set KansasN=Kansas
		set KentuckyN=Kentucky
		set LouisianaN=Louisiana
		set MassachusettsN=Massachusetts
		set MarylandN=Maryland
		set MaineN=Maine
		set MichiganN=Michigan
		set MinnesotaN=Minnesota
		set MissouriN=Missouri
		set MississippiN=Mississippi
		set MontanaN=Montana
		set NorthCarolinaN=North Carolina
		set NorthDakotaN=North Dakota
		set NebraskaN=Nebraska
		set NewHampshireN=New Hampshire
		set NewJerseyN=New Jersey
		set NewMexicoN=New Mexico
		set NevadaN=Nevada
		set NewYorkN=New York
		set OhioN=Ohio
		set OklahomaN=Oklahoma
		set OregonN=Oregon
		set PennsylvaniaN=Pennsylvania
		set RhodeIslandN=RhodeIsland
		set SouthCarolinaN=South Carolina
		set SouthDakotaN=South Dakota
		set TennesseeN=Tennessee
		set TexasN=Texas
		set UtahN=Utah
		set VirginiaN=Virginia
		set VermontN=Vermont
		set WashingtonN=Washington
		set WisconsinN=Wisconsin
		set WestVirginiaN=West Virginia
		set WyomingN=Wyoming

------------------------------------------------------------------------------------------------
REM set the board status here or Set up
	:Main	
		cls
		echo Initial Set Up Press #99
		echo 
		echo Dr. %DocFirst% %DocLast% is Board Certified in?
		echo.
		echo #1 %BC_One_ON%
		echo #2 %BC_Two_ON%
		echo #3 %BC_Three_ON%
		echo #4 %BC_Four_ON%
		echo #5 %BC_Five_ON%
		echo #6 %BC_Six_ON%
		echo #7 %BC_Seven_ON%
		echo #8 %BC_Eight_ON%
		echo # 



		echo.
		SET /P M=Board Certified in?:
		IF %M%==1 GOTO Boarded_One
		IF %M%==2 GOTO Boarded_Two
		IF %M%==3 GOTO Boarded_Three
		IF %M%==4 GOTO Boarded_Four
		IF %M%==5 GOTO Boarded_Five
		IF %M%==6 GOTO Boarded_Six
		IF %M%==7 GOTO Boarded_Seven
		IF %M%==8 GOTO Boarded_Eight
        
		IF %M%==99 GOTO SetUp

		IF not
		"%INPUT%"=="somestupidvaluethatoneonewilleverfindunlesstheylookatthis" GOTO Error

		
Rem NEED TO START WORKING FROM HERE
			:Boarded_One
				set BC_One=%BC_One_ON%
				
			GOTO Main
			-----------------------------------------------------------
			:Boarded_Two
				set BC_Two=%BC_Two_ON%

			GOTO Main
			-----------------------------------------------------------
			:Boarded_Three
				set BC_Three=%BC_Three_ON%
				
			GOTO Main
			-------------------------------------------------------
			:Boarded_Four
				set BC_Four=%BC_Four_ON%
				
			GOTO Main
-------------------------------------------------------
			:Boarded_Five
				set BC_Five=%BC_Five_ON%
				
			GOTO Main
			-------------------------------------------------------
			:Boarded_Six
				set BC_Six=%BC_Six_ON%
				
			GOTO Main
			-------------------------------------------------------
			:Boarded_Seven
				set BC_Seven=%BC_Seven_ON%
				
			GOTO Main
			-------------------------------------------------------
			:Boarded_Eight
				set BC_Eight=%BC_Eight_ON%
				
			GOTO Main
			-------------------------------------------------------
		
				
				
				
				
				:AnatomicClinical1Fellow
					cls


					cls
					echo Fellowship in?
					echo.
					echo #1 General Surgical Pathology
					echo #2 Neuropathology 
					echo #3 Cytopathology
					echo #4 Dermatopathology
					echo #5 Hematopathology
					echo #6 Other


					echo.
					SET /P M=Board Certified in?:
					IF %M%==1 GOTO Gen
					IF %M%==2 GOTO Neur
					IF %M%==3 GOTO Cyto
					IF %M%==4 GOTO Derm
					IF %M%==5 GOTO Hema
					IF %M%==6 GOTO Other
					IF not
					"%INPUT%"=="somestupidvaluethatoneonewilleverfindunlesstheylookatthis" GOTO Error

						:Gen
							cls

							set VarFellowOne=General Surgical Pathology 
							set BC_One=Anatomic and
							set BC_Two=Clinical

						GOTO CaseloadNew
							-----------
						:Neur
							cls

							set VarFellowOne=Neuropathology 
							set BC_One=Anatomic and
							set BC_Two=Clinical

						GOTO CaseloadNew
							-----------
						:Cyto
							cls

							set VarFellowOne=Cytopathology 
							set BC_One=Anatomic and
							set BC_Two=Clinical

						GOTO CaseloadNew
						-----------
						:Derm
							cls

							set VarFellowOne=Dermatopathology 
							set BC_One=Anatomic and
							set BC_Two=Clinical

						GOTO CaseloadNew
						-----------
						:Hema
							cls

							set VarFellowOne=Hematopathology 
							set BC_One=Anatomic and
							set BC_Two=Clinical

						GOTO CaseloadNew
						-----------
						:Other
							cls
							set /p VarOtherOne=Other Fellowship: 
							set VarFellowOne=%VarOtherOne%
							set BC_One=Anatomic and
							set BC_Two=Clinical

					GOTO CaseloadNew
					
------------------------------------------------------------------------------------------------				
					
	REM set default restriction values
		set Restriction_One_N=- GI Pathology
		set Restriction_Two_N=- GU Pathology
		set Restriction_Three_N=- Neuropathology
		set Restriction_Four_N=- Dermatopathology
		set Restriction_Five_N=- Hematopathology
		set Restriction_Six_N=- Aspiration of bone marrow
		set Restriction_Seven_N=- Interpretation of bone marrow					
		set Restriction_Eight_N=- Pediatric tumor pathology
		set Restriction_Nine_N=- GYN Cytology					
		set Restriction_Ten_N=- Non-GYN Cytology	
		set Restriction_Eleven_N=- Performance of FNA's
		set Restriction_Twelve_N=- Autopsy
		set Restriction_Thirteen_N=
		set Restriction_Fourteen_N=
		set Restriction_Fifteen_N=
		set Restriction_Sixteen_N=
		set Restriction_Seventeen_N=
		set Restriction_Eightteen_N=
		set Restriction_Nineteen_N=
		set Restriction_Twenty_N=
------------------------------------------------------------------------------------------------
REM set the software here
			:CaseloadNew
				cls
				echo Dr. %DocFirst% %DocLast% Has what Skills On CC Form?
				echo.
				echo #1  %GIPathY% GI Pathology              
				echo #2  %GUPathY% GU Pathology        
				echo #3  %NeuroPathY% Neuropathology           
				echo #4  %DermPathY% Dermatopathology         
				echo #5  %HemaPathY% Hematopathology
				echo #6  %AspirationY% Aspiration of bone marrow
				echo #7  %InterpertationY% Interpretation of bone marrow
				echo #8  %PedY% Pediatric tumor pathology
				echo #9  %GYNY% GYN Cytology
				echo #10 %Non-GYNY% Non-GYN Cytology
				echo #11 %FNAY% Performance of FNA's
				echo #12 %AutopsyY% Autopsy							
				echo.							
				echo #13 Done

				

				echo.
				SET /P M=Make your selection?:
					IF %M%==1 GOTO GIPath
					IF %M%==2 GOTO GUPath
					IF %M%==3 GOTO NeuroPath
					IF %M%==4 GOTO DermPath
					IF %M%==5 GOTO HemaPath
					IF %M%==6 GOTO Aspiration
					IF %M%==7 GOTO Interpertation
					IF %M%==8 GOTO Ped
					IF %M%==9 GOTO GYN
					IF %M%==10 GOTO Non-GYN
					IF %M%==11 GOTO FNA
					IF %M%==12 GOTO Autopsy
					IF %M%==13 GOTO Software
				IF not
				"%INPUT%"=="somestupidvaluethatoneonewilleverfindunlesstheylookatthis" GOTO Error	
					:GIPath
						set GIPath=GI Pathology,
						set GIPathY=(ON)
						set Restriction_One_N=-
					GOTO CaseloadNew
				----------------------
					:GUPath
						set GUPath= GU Pathology,
						set GUPathY=(ON)
						set Restriction_Two_N=-
					GOTO CaseloadNew
				----------------------
					:NeuroPath
						set NeuroPath= Neuropathology,
						set NeuroPathY=(ON)
						set Restriction_Three_N=-
					GOTO CaseloadNew
				----------------------
					:DermPath
						set DermPath= Dermatopathology,
						set DermPathY=(ON)
						set Restriction_Four_N=-
					GOTO CaseloadNew
				----------------------
					:HemaPath
						set HemaPath= Hematopathology,
						set HemaPathY=(ON)
						set Restriction_Five_N=-
					GOTO CaseloadNew
				----------------------
					:Aspiration
						set Aspiration= Aspiration of bone marrow,
						set AspirationY=(ON)
						set Restriction_Six_N=-
					GOTO CaseloadNew
				----------------------
					:Interpertation
						set Interpertation= Interpretation of bone marrow,
						set InterpertationY=(ON)
						set Restriction_Seven_N=-
					GOTO CaseloadNew
				----------------------
					:Ped
						set Ped= Pediatric tumor pathology,
						set PedY=(ON)
						set Restriction_Eight_N=-
					GOTO CaseloadNew
				----------------------
					:GYN
						set GYN= GYN Cytology,
						set GYNY=(ON)
						set Restriction_Nine_N=-
					GOTO CaseloadNew
				----------------------
					:Non-GYN
						set Non-GYN= Non-GYN Cytology,
						set Non-GYNY=(ON)
						set Restriction_Ten_N=-
					GOTO CaseloadNew
				----------------------
					:FNA
						set FNA= Performance of FNA's,
						set FNAY=(ON)
						set Restriction_Eleven_N=-
					GOTO CaseloadNew

				----------------------
					:Autopsy
						set Autopsy= and Autopsy
						set AutopsyY=(ON)
						set Restriction_Twelve_N=-
			GOTO CaseloadNew
------------------------------------------------------------------------------
REM set the software here
	:Software
			cls
			echo Dr %DocFirst% %DocLast% is familiar with what lab computer systems?
			echo.
			echo #1 %APEasyY% APEasy                 
			echo #2 %SoftPathY% SoftPath              
			echo #3 %CoPathY% CoPath               
			echo #4 %PowerPathY% PowerPath             
			echo #5 %MeditechY% Meditech 
			echo #6 %EPICY% EPIC 
			echo #7 %MillenniumY% Millennium 
			echo #8 %CernerY% Cerner 
			echo.							
			echo #13 Done

			

			echo.
			SET /P M=Make your selection?:
				IF %M%==1 GOTO APEasy
				IF %M%==2 GOTO SoftPath
				IF %M%==3 GOTO CoPath
				IF %M%==4 GOTO PowerPath
				IF %M%==5 GOTO Meditech
				IF %M%==6 GOTO EPIC
				IF %M%==7 GOTO Millennium
				IF %M%==8 GOTO Cerner
				IF %M%==13 GOTO License

			IF not
			"%INPUT%"=="somestupidvaluethatoneonewilleverfindunlesstheylookatthis" GOTO Error	

			
				:APEasy
					set APEasy=APEasy
					set APEasyY=(ON)
				GOTO Software
			
				:SoftPath
					Set SoftPath=, SoftPath
					set SoftPathY=(ON)
				GOTO Software
				
				:CoPath
					set CoPath=, CoPath
					set CoPathY=(ON)
				GOTO Software
				
				:PowerPath
					set PowerPath=, PowerPath 
					set PowerPathy=(ON)
				GOTO Software
				
				:Meditech
					set Meditech=, Meditech 
					set MeditechY=(ON)
				GOTO Software
				
				:EPIC
					set EPIC=, EPIC
					set EPICY=(ON)
				GOTO Software
				
				:Millennium
					set Millennium=, Millennium
					set MillenniumY=(ON)
				GOTO Software
				
				:Cerner
					set Cerner=, Cerner
					set CernerY=(ON)
				GOTO Software	
			
------------------------------------------------------------------------------------------------
REM set the software here						
	:License	
			cls
			echo Dr %DocFirst% %DocLast% is Licensed in?
			echo.
			echo %AlaskaY% Alaska
			echo %AlabamaY% Alabama 
			echo %ArkansasY% Arkansas
			echo %ArizonaY% Arizona
			echo %CaliforniaY% California
			echo %ColoradoY% Colorado
			echo %ConnecticutY% Connecticut 
			echo %DelawareY% Delaware 
			echo %FloridaY% Florida
			echo %GeorgiaY% Georgia
			echo %HawaiiY% Hawaii
			echo %IowaY% Iowa 
			echo %IdahoY% Idaho 
			echo %IllinoisY% Illinois
			echo %IndianaY% Indiana 
			echo %KansasY% Kansas 
			echo %KentuckyY% Kentucky 
			echo %LouisianaY% Louisiana 
			echo %MassachusettsY% Massachusetts
			echo %MarylandY% Maryland 
			echo %MaineY% Maine 
			echo %MichiganY% Michigan
			echo %MinnesotaY% Minnesota
			echo %MissouriY% Missouri 
			echo %MississippiY% Mississippi 
			echo %MontanaY% Montana 
			echo %NorthCarolinaY% NorthCarolina
			echo %NorthDakotaY% NorthDakota 
			echo %NebraskaY% Nebraska 
			echo %NewHampshireY% NewHampshire 
			echo %NewJerseyY% NewJersey
			echo %NewMexicoY% NewMexico 
			echo %NevadaY% Nevada 
			echo %NewYorkY% New York 
			echo %OhioY% Ohio
			echo %OklahomaY% Oklahoma 
			echo %OregonY% Oregon 
			echo %PennsylvaniaY% Pennsylvania
			echo %RhodeIslandY% Rhode Island 
			echo %SouthCarolinaY% South Carolina 
			echo %SouthDakotaY% South Dakota
			echo %TennesseeY% Tennessee
			echo %TexasY% Texas
			echo %UtahY% Utah
			echo %VirginiaY% Virginia
			echo %VermontY% Vermont
			echo %WashingtonY% Washington
			echo %WisconsinY% Wisconsin
			echo %WestVirginiaY% WestVirginia
			echo %WyomingY% Wyoming
			echo.							
			echo #13 Done

			
			echo.
			SET /P M=Make your selection?:
				IF %M%==AK GOTO Alaska 
				IF %M%==AL GOTO Alabama 
				IF %M%==AR GOTO Arkansas 
				IF %M%==AZ GOTO Arizona 
				IF %M%==CA GOTO California 
				IF %M%==CO GOTO Colorado 
				IF %M%==CT GOTO Connecticut 
				IF %M%==DE GOTO Delaware 
				IF %M%==FL GOTO Florida 
				IF %M%==GA GOTO Georgia 
				IF %M%==HI GOTO Hawaii 
				IF %M%==IA GOTO Iowa 
				IF %M%==ID GOTO Idaho 
				IF %M%==IL GOTO Illinois 
				IF %M%==IN GOTO Indiana 
				IF %M%==KS GOTO Kansas 
				IF %M%==KY GOTO Kentucky 
				IF %M%==LA GOTO Louisiana 
				IF %M%==MA GOTO Massachusetts 
				IF %M%==MD GOTO Maryland 
				IF %M%==ME GOTO Maine 
				IF %M%==MI GOTO Michigan 
				IF %M%==MN GOTO Minnesota 
				IF %M%==MO GOTO Missouri 
				IF %M%==MS GOTO Mississippi 
				IF %M%==MT GOTO Montana 
				IF %M%==NC GOTO NorthCarolina 
				IF %M%==ND GOTO NorthDakota 
				IF %M%==NE GOTO Nebraska 
				IF %M%==NE GOTO NewHampshire 
				IF %M%==NJ GOTO NewJersey 
				IF %M%==NM GOTO NewMexico 
				IF %M%==NV GOTO Nevada 
				IF %M%==NY GOTO NewYork 
				IF %M%==OH GOTO Ohio 
				IF %M%==OK GOTO Oklahoma 
				IF %M%==OR GOTO Oregon 
				IF %M%==PA GOTO Pennsylvania 
				IF %M%==RI GOTO RhodeIsland 
				IF %M%==SC GOTO SouthCarolina 
				IF %M%==SD GOTO SouthDakota 
				IF %M%==TN GOTO Tennessee 
				IF %M%==TX GOTO Texas 
				IF %M%==UT GOTO Utah 
				IF %M%==VA GOTO Virginia 
				IF %M%==VT GOTO Vermont 
				IF %M%==WA GOTO Washington 
				IF %M%==WI GOTO Wisconsin 
				IF %M%==WV GOTO WestVirginia 
				IF %M%==WY GOTO Wyoming 
				IF %M%==13 GOTO Ref				

			IF not
			"%INPUT%"=="somestupidvaluethatoneonewilleverfindunlesstheylookatthis" GOTO Error	
		
				:Alaska
					set Alaska= Alaska
					set AlaskaY=(ON)
					set AlaskaN=-						
				GOTO License
				:Alabama
					set Alabama= Alabama
					set AlabamaY=(ON)
					set AlabamaN=-							
				GOTO License
				:Arkansas
					set Arkansas=, Arkansas
					set ArkansasY=(ON)
					set ArkansasN=-							
				GOTO License
				:Arizona
					set Arizona=, Arizona
					set ArizonaY=(ON)
					set ArizonaN=-						
				GOTO License
				:California 
					set California=, California
					set CaliforniaY=(ON)
					set CaliforniaN=-							
				GOTO License
				:Colorado 
					set Colorado=, Colorado
					set	ColoradoY=(ON)
					set	ColoradoN=-						
				GOTO License							
				:Connecticut 
					set Connecticut=, Connecticut
					set	ConnecticutY=(ON)
					set	ConnecticutN=-							
				GOTO License							
				:Delaware 
					set Delaware=, Delaware
					set	DelawareY=(ON)
					set	DelawareN=-							
				GOTO License							
				:Florida 
					set Florida=, Florida
					set	FloridaY=(ON)	
					set	FloridaN=-							
				GOTO License							
				:Georgia
					set Georgia=, Georgia
					set	GeorgiaY=(ON)
					set	GeorgiaN=-							
				GOTO License							
				:Hawaii
					set Hawaii=, Hawaii
					set	HawaiiY=(ON)
					set	HawaiiN=-						
				GOTO License							
				:Iowa
					set Iowa=, Iowa
					set	IowaY=(ON)
					set	IowaN=-							
				GOTO License
				:Idaho 
					set Idaho=, Idaho 
					set	IdahoY=(ON)	
					set	IdahoN=-							
				GOTO License
				:Illinois
					set Illinois=, Illinois
					set	IllinoisY=(ON)
					set	IllinoisN=-						
				GOTO License
				:Indiana 
					set Indiana=, Indiana 
					set	IndianaY=(ON)	
					set	IndianaN=-						
				GOTO License
				:Kansas 
					set Kansas=, Kansas
					set	KansasY=(ON)	
					set	KansasN=-							
				GOTO License
				:Kentucky 
					set Kentucky=, Kentucky
					set	KentuckyY=(ON)
					set	KentuckyN=-							
				GOTO License
				:Louisiana 
					set Louisiana=, Louisiana 
					set	LouisianaY=(ON)
					set	LouisianaN=-							
				GOTO License
				:Massachusetts
					set Massachusetts=, Massachusetts
					set	MassachusettsY=(ON)
					set	MassachusettsN=-							
				GOTO License
				:Maryland 
					set Maryland=, Maryland
					set	MarylandY=(ON)
					set	MarylandN=-							
				GOTO License
				:Maine 
					set Maine=, Maine 
					set	MaineY=(ON)	
					set	MaineN=-							
				GOTO License
				:Michigan 
					set Michigan=, Michigan
					set	MichiganY=(ON)
					set	MichiganN=-							
				GOTO License
				:Minnesota 
					set Minnesota=, Minnesota
					set	MinnesotaY=(ON)
					set	MinnesotaN=-							
				GOTO License
				:Missouri 
					set Missouri=, Missouri 
					set	MissouriY=(ON)
					set	MissouriN=-							
				GOTO License
				:Mississippi
					set Mississippi=, Mississippi 
					set	MississippiY=(ON)
					set	MississippiN=-							
				GOTO License
				:Montana 
					set Montana=, Montana 
					set	MontanaY=(ON)	
					set	MontanaN=-								
				GOTO License
				:NorthCarolina 
					set NorthCarolina=, North Carolina
					set	NorthCarolinaY=(ON)
					set	NorthCarolinaN=-							
				GOTO License
				:NorthDakota 
					set NorthDakota=, North Dakota 
					set	NorthDakotaY=(ON)
					set	NorthDakotaN=-							
				GOTO License
				:Nebraska 
					set Nebraska=, Nebraska 
					set	NebraskaY=(ON)
					set	NebraskaN=-							
				GOTO License
				:NewHampshire 
					set NewHampshire=, NewHampshire
					set	NewHampshireY=(ON)
					set	NewHampshireN=-							
				GOTO License
				:NewJersey 
					set NewJersey=, NewJersey
					set	NewJerseyY=(ON)
					set	NewJerseyN=-							
				GOTO License
				:NewMexico 
					set NewMexico=, NewMexico
					set	NewMexicoY=(ON)
					set	NewMexicoN=-						
				GOTO License
				:Nevada 
					set Nevada=, Nevada
					set	NevadaY=(ON)	
					set	NevadaN=-							
				GOTO License
				:NewYork 
					set NewYork=, New York 
					set	NewYorkY=(ON)	
					set	NewYorkN=-							
				GOTO License
				:Ohio 
					set Ohio=, Ohio
					set	OhioY=(ON)
					set	OhioN=-							
				GOTO License
				:Oklahoma 
					set Oklahoma=, Oklahoma
					set	OklahomaY=(ON)
					set	OklahomaN=-							
				GOTO License
				:Oregon 
					set Oregon=, Oregon 
					set	OregonY=(ON)	
					set	OregonN=-								
				GOTO License
				:Pennsylvania 
					set Pennsylvania=, Pennsylvania
					set	PennsylvaniaY=(ON)
					set	PennsylvaniaN=-							
				GOTO License
				:RhodeIsland 
					set RhodeIsland=, Rhode Island 
					set	RhodeIslandY=(ON)	
					set	RhodeIslandN=-								
				GOTO License
				:SouthCarolina
					set SouthCarolina=, South Carolina 
					set	SouthCarolinaY=(ON)
					set	SouthCarolinaN=-							
				GOTO License
				:SouthDakota 
					set SouthDakota=, South Dakota
					set	SouthDakotaY=(ON)	
					set	SouthDakotaN=-								
				GOTO License
				:Tennessee 
					set Tennessee=, Tennessee
					set	TennesseeY=(ON)
					set	TennesseeN=-							
				GOTO License
				:Texas 
					set Texas=, Texas
					set	TexasY=(ON)	
					set	TexasN=-							
				GOTO License
				:Utah 
					set Utah=, Utah
					set	UtahY=(ON)
					set	UtahN=-							
				GOTO License
				:Virginia 
					set Virginia=, Virginia
					set	VirginiaY=(ON)
					set	VirginiaN=-							
				GOTO License
				:Vermont 
					set Vermont=, Vermont
					set	VermontY=(ON)	
					set	VermontN=-								
				GOTO License
				:Washington 
					set Washington=, Washington
					set	WashingtonY=(ON)
					set	WashingtonN=-							
				GOTO License
				:Wisconsin 
					set Wisconsin=, Wisconsin
					set	WisconsinY=(ON)
					set	WisconsinN=-							
				GOTO License
				:WestVirginia 
					set WestVirginia=, West Virginia
					set	WestVirginiaY=(ON)
					set	WestVirginiaN=-							
				GOTO License
				:Wyoming 
					set Wyoming=,and Wyoming
					set	WyomingY=(ON)	
					set	WyomingN=-							
			GOTO License

			
------------------------------------------------------------------------------------------------
REM this is the list of references
	:Ref
	
		cls
		set /p VarTwenty=Reference #1 Name:
		set /p VarTwentyOne=Reference #1 Phone#: 
			cls
			set /p VarTwentyTwo=Reference #2 Name:
			set /p VarTwentyThree=Reference #2 Phone#: 
			cls
				set /p VarTwentyFour=Reference #3 Name:
				set /p VarTwentyFive=Reference #3 Phone#: 
				cls
		GOTO Print
		
------------------------------------------------------------------------------------------------
REM enter the desired output here
:Print
		echo - Dr. %DocLast% is Board Certified in %VarFellowOne%as well as %BC_One% %BC_Two% Pathology>> %Output%\Dr_%DocFirst%_%DocLast%.txt
				echo. >> %Output%\Dr_%DocFirst%_%DocLast%.txt
		echo Why Doing Locums? >> %Output%\Dr_%DocFirst%_%DocLast%.txt
				echo. >> %Output%\Dr_%DocFirst%_%DocLast%.txt
		echo - Skill set includes: %GIPath%%GUPath%%NeuroPath%%DermPath%%HemaPath%%Aspiration%%Interpertation%%Ped%%GYN%%Non-GYN%%FNA%%Autopsy%>> %Output%\Dr_%DocFirst%_%DocLast%.txt
				echo. >> %Output%\Dr_%DocFirst%_%DocLast%.txt
		echo - Dr. %DocLast% has unrestricted medical licenses in%Arkansas%%Arizona%%California%%Colorado%%Connecticut%%Delaware%%Florida%%Georgia%%Hawaii%%Iowa%%Idaho%%Illinois%%Indiana%%Kansas%%Kentucky%%Louisiana%%Massachuechots%%Maryland%%Maine%%Michigan%%Minnesota%%Missouri%%Mississippi%%Montana%%NorthCarolina%%NorthDakota%%Nebraska%%NewHampshire%%NewJersey%%NewMexico%%Nevada%%NewYork%%Ohio%%Oklahoma%%Oregon%%Pennsylvania%%RhodeIsland%%SouthCarolina%%SouthDakota%%Tennessee%%Texas%%Utah%%Virginia%%Vermont%%Washington%%Wisconsin%%WestVirginia%%Wyoming%>> %Output%\Dr_%DocFirst%_%DocLast%.txt
				echo. >> %Output%\Dr_%DocFirst%_%DocLast%.txt
		echo - Familiar with %APEasy%%SoftPath%%CoPath%%PowerPath%%Meditech%%EPIC%%Millennium%%Cerner% and other lab computer systems%High4% >> %Output%\Dr_%DocFirst%_%DocLast%.txt
				echo. >> %Output%\Dr_%DocFirst%_%DocLast%.txt
		echo - Current references:>> %Output%\Dr_%DocFirst%_%DocLast%.txt
				echo. >> %Output%\Dr_%DocFirst%_%DocLast%.txt
		echo     * Dr. %VarTwenty%, Pathologist, %VarTwentyOne% >> %Output%\Dr_%DocFirst%_%DocLast%.txt
				echo. >> %Output%\Dr_%DocFirst%_%DocLast%.txt
		echo     * Dr. %VarTwentyTwo%, Pathologist, %VarTwentyThree% >> %Output%\Dr_%DocFirst%_%DocLast%.txt
				echo. >> %Output%\Dr_%DocFirst%_%DocLast%.txt
		echo     * Dr. %VarTwentyFour%, Pathologist, %VarTwentyFive% >> %Output%\Dr_%DocFirst%_%DocLast%.txt
				echo. >> %Output%\Dr_%DocFirst%_%DocLast%.txt
				echo. >> %Output%\Dr_%DocFirst%_%DocLast%.txt
		echo - Current references available upon request >> %Output%\Dr_%DocFirst%_%DocLast%.txt
				echo. >> %Output%\Dr_%DocFirst%_%DocLast%.txt
				echo. >> %Output%\Dr_%DocFirst%_%DocLast%.txt
		echo -----------Restrictions---------------------------------------------------------------- >> %Output%\Dr_%DocFirst%_%DocLast%.txt
				echo. >> %Output%\Dr_%DocFirst%_%DocLast%.txt
				echo. >> %Output%\Dr_%DocFirst%_%DocLast%.txt
			echo Restrictions:>> %Output%\Dr_%DocFirst%_%DocLast%.txt
			echo. >> %Output%\Dr_%DocFirst%_%DocLast%.txt
			echo %Restriction_One_N%>> %Output%\Dr_%DocFirst%_%DocLast%.txt 
			echo %Restriction_Two_N%>> %Output%\Dr_%DocFirst%_%DocLast%.txt
			echo %Restriction_Three_N%>> %Output%\Dr_%DocFirst%_%DocLast%.txt
			echo %Restriction_Four_N%>> %Output%\Dr_%DocFirst%_%DocLast%.txt
			echo %Restriction_Five_N%>> %Output%\Dr_%DocFirst%_%DocLast%.txt
			echo %Restriction_Six_N%>> %Output%\Dr_%DocFirst%_%DocLast%.txt
			echo %Restriction_Seven_N%>> %Output%\Dr_%DocFirst%_%DocLast%.txt
			echo %Restriction_Eight_N%>> %Output%\Dr_%DocFirst%_%DocLast%.txt
			echo %Restriction_Nine_N%>> %Output%\Dr_%DocFirst%_%DocLast%.txt
			echo %Restriction_Ten_N%>> %Output%\Dr_%DocFirst%_%DocLast%.txt
			echo %Restriction_Eleven_N%>> %Output%\Dr_%DocFirst%_%DocLast%.txt
			echo %Restriction_Twelve_N%>> %Output%\Dr_%DocFirst%_%DocLast%.txt
				echo. >> %Output%\Dr_%DocFirst%_%DocLast%.txt
				echo. >> %Output%\Dr_%DocFirst%_%DocLast%.txt
		echo -----------------Malpractice---------------------------------------------------------- >> %Output%\Dr_%DocFirst%_%DocLast%.txt
					echo. >> %Output%\Dr_%DocFirst%_%DocLast%.txt
					echo. >> %Output%\Dr_%DocFirst%_%DocLast%.txt
			echo Malpractice: >> %Output%\Dr_%DocFirst%_%DocLast%.txt
					echo. >> %Output%\Dr_%DocFirst%_%DocLast%.txt

			echo - Dr. %DocLast% does not have any medical malpractice cases or disciplinary actions>> %Output%\Dr_%DocFirst%_%DocLast%.txt
					echo. >> %Output%\Dr_%DocFirst%_%DocLast%.txt

			echo - Dr. %DocLast% has never been named in a malpractice suit >> %Output%\Dr_%DocFirst%_%DocLast%.txt
					echo. >> %Output%\Dr_%DocFirst%_%DocLast%.txt

			echo - Dr. %DocLast% has no history of medical malpractice >> %Output%\Dr_%DocFirst%_%DocLast%.txt
					echo. >> %Output%\Dr_%DocFirst%_%DocLast%.txt


			echo - Dr. %DocLast% has been named in _____ malpractice case in _____, was settled out of court for $______ >> %Output%\Dr_%DocFirst%_%DocLast%.txt
					echo. >> %Output%\Dr_%DocFirst%_%DocLast%.txt

			echo - Dr. %DocLast% has been named in __ malpractice case/cases that was/were dismissed >> %Output%\Dr_%DocFirst%_%DocLast%.txt

					echo. >> %Output%\Dr_%DocFirst%_%DocLast%.txt
					echo. >> %Output%\Dr_%DocFirst%_%DocLast%.txt
		echo ------------------Extra-Board Status--------------------------------------------------------- >> %Output%\Dr_%DocFirst%_%DocLast%.txt
					echo. >> %Output%\Dr_%DocFirst%_%DocLast%.txt
					echo. >> %Output%\Dr_%DocFirst%_%DocLast%.txt

			echo - Dr. %DocLast% is board certified in %VarFellowOne% as well as Anatomic and Clinical Pathology >> %Output%\Dr_%DocFirst%_%DocLast%.txt
					echo. >> %Output%\Dr_%DocFirst%_%DocLast%.txt

			echo - Dr. %DocLast% has __ years of pathology experience and is Fellowship trained in ______ Pathology and ______ >> %Output%\Dr_%DocFirst%_%DocLast%.txt
					echo. >> %Output%\Dr_%DocFirst%_%DocLast%.txt

			echo - Dr. %DocLast% is board certified in Anatomic and Clinical pathology with additional fellowship training and abundant experience in %VarFellowOne% pathology>> %Output%\Dr_%DocFirst%_%DocLast%.txt
		
					echo. >> %Output%\Dr_%DocFirst%_%DocLast%.txt
					echo. >> %Output%\Dr_%DocFirst%_%DocLast%.txt
		echo ------------------Why Doing Locums--------------------------------------------------------- >> %Output%\Dr_%DocFirst%_%DocLast%.txt
					echo. >> %Output%\Dr_%DocFirst%_%DocLast%.txt
					echo. >> %Output%\Dr_%DocFirst%_%DocLast%.txt

			echo - Dr. %DocLast% is currently a in a group in _______, ___ and would like to provide locum work with his/her extra vacation time >> %Output%\Dr_%DocFirst%_%DocLast%.txt
					echo. >> %Output%\Dr_%DocFirst%_%DocLast%.txt

			echo - Dr. %DocLast% full-time position in _______, ___ affords him/her a great deal of free time and flexibility to provide locums coverage>> %Output%\Dr_%DocFirst%_%DocLast%.txt
					echo. >> %Output%\Dr_%DocFirst%_%DocLast%.txt

			echo - Dr. %DocLast% is currently a in a group in _______, ___ and would like to provide ____ -____ weeks of locums coverage per year with his/her free time >> %Output%\Dr_%DocFirst%_%DocLast%.txt
					echo. >> %Output%\Dr_%DocFirst%_%DocLast%.txt

			echo - Dr. %DocLast% has found locum's to be a wonderful way to expand experience, improve skills, and expand services in their own practice>> %Output%\Dr_%DocFirst%_%DocLast%.txt
					echo. >> %Output%\Dr_%DocFirst%_%DocLast%.txt

			echo - Dr. %DocLast% is local and can commute daily >> %Output%\Dr_%DocFirst%_%DocLast%.txt
					echo. >> %Output%\Dr_%DocFirst%_%DocLast%.txt

			echo - Dr. %DocLast% is currently credentialed with CompHealth >> %Output%\Dr_%DocFirst%_%DocLast%.txt  
					echo. >> %Output%\Dr_%DocFirst%_%DocLast%.txt

			echo - Dr. %DocLast% is currently credentialed with CompHealth and has provided locums with great success >> %Output%\Dr_%DocFirst%_%DocLast%.txt
					echo. >> %Output%\Dr_%DocFirst%_%DocLast%.txt

			echo - Dr. %DocLast% has completed several locum's assignments for CompHealth >> %Output%\Dr_%DocFirst%_%DocLast%.txt
					echo. >> %Output%\Dr_%DocFirst%_%DocLast%.txt

			echo - Dr. %DocLast% has completed numerous locum's assignments for CompHealth with request for repeat assignments >> %Output%\Dr_%DocFirst%_%DocLast%.txt
			
			echo - Dr. %DocLast% is comfortable with a very heavy case load 150+ CPT’s daily>> %Output%\Dr_%DocFirst%_%DocLast%.txt
					echo. >> %Output%\Dr_%DocFirst%_%DocLast%.txt

			echo - Dr. %DocLast% is comfortable with the clients practice description>> %Output%\Dr_%DocFirst%_%DocLast%.txt
					echo. >> %Output%\Dr_%DocFirst%_%DocLast%.txt
					echo. >> %Output%\Dr_%DocFirst%_%DocLast%.txt

		echo ------------------Inactive State License--------------------------------------------------------- >> %Output%\Dr_%DocFirst%_%DocLast%.txt
					echo. >> %Output%\Dr_%DocFirst%_%DocLast%.txt
					echo. >> %Output%\Dr_%DocFirst%_%DocLast%.txt

			echo - Dr. %DocLast% does not currently hold an active ________ license>> %Output%\Dr_%DocFirst%_%DocLast%.txt 
					echo. >> %Output%\Dr_%DocFirst%_%DocLast%.txt
					
			REM lists licences Dr does not have
			echo **NOTE: Dr. %DocLast% does NOT have any of the following state licences** >> %Output%\Dr_%DocFirst%_%DocLast%.txt
				echo. >> %Output%\Dr_%DocFirst%_%DocLast%.txt
				
				echo %AlabamaN% >> %Output%\Dr_%DocFirst%_%DocLast%.txt											
				echo %AlaskaN% >> %Output%\Dr_%DocFirst%_%DocLast%.txt
				echo %ArkansasN% >> %Output%\Dr_%DocFirst%_%DocLast%.txt
				echo %ArizonaN% >> %Output%\Dr_%DocFirst%_%DocLast%.txt
				echo %CaliforniaN% >> %Output%\Dr_%DocFirst%_%DocLast%.txt
				echo %ColoradoN% >> %Output%\Dr_%DocFirst%_%DocLast%.txt
				echo %ConnecticutN% >> %Output%\Dr_%DocFirst%_%DocLast%.txt
				echo %DelawareN% >> %Output%\Dr_%DocFirst%_%DocLast%.txt
				echo %FloridaN% >> %Output%\Dr_%DocFirst%_%DocLast%.txt
				echo %GeorgiaN% >> %Output%\Dr_%DocFirst%_%DocLast%.txt
				echo %HawaiiN% >> %Output%\Dr_%DocFirst%_%DocLast%.txt
				echo %IowaN% >> %Output%\Dr_%DocFirst%_%DocLast%.txt
				echo %IdahoN% >> %Output%\Dr_%DocFirst%_%DocLast%.txt
				echo %IllinoisN% >> %Output%\Dr_%DocFirst%_%DocLast%.txt
				echo %IndianaN% >> %Output%\Dr_%DocFirst%_%DocLast%.txt
				echo %KansasN% >> %Output%\Dr_%DocFirst%_%DocLast%.txt
				echo %KentuckyN% >> %Output%\Dr_%DocFirst%_%DocLast%.txt
				echo %LouisianaN% >> %Output%\Dr_%DocFirst%_%DocLast%.txt
				echo %MassachuechotsN% >> %Output%\Dr_%DocFirst%_%DocLast%.txt
				echo %MarylandN% >> %Output%\Dr_%DocFirst%_%DocLast%.txt
				echo %MaineN% >> %Output%\Dr_%DocFirst%_%DocLast%.txt
				echo %MichiganN% >> %Output%\Dr_%DocFirst%_%DocLast%.txt
				echo %MinnesotaN% >> %Output%\Dr_%DocFirst%_%DocLast%.txt
				echo %MissouriN% >> %Output%\Dr_%DocFirst%_%DocLast%.txt
				echo %MississippiN% >> %Output%\Dr_%DocFirst%_%DocLast%.txt
				echo %MontanaN% >> %Output%\Dr_%DocFirst%_%DocLast%.txt
				echo %NorthCarolinaN% >> %Output%\Dr_%DocFirst%_%DocLast%.txt
				echo %NorthDakotaN% >> %Output%\Dr_%DocFirst%_%DocLast%.txt
				echo %NebraskaN% >> %Output%\Dr_%DocFirst%_%DocLast%.txt
				echo %NewHampshireN% >> %Output%\Dr_%DocFirst%_%DocLast%.txt
				echo %NewJerseyN% >> %Output%\Dr_%DocFirst%_%DocLast%.txt
				echo %NewMexicoN% >> %Output%\Dr_%DocFirst%_%DocLast%.txt
				echo %NevadaN% >> %Output%\Dr_%DocFirst%_%DocLast%.txt
				echo %NewYorkN% >> %Output%\Dr_%DocFirst%_%DocLast%.txt
				echo %OhioN% >> %Output%\Dr_%DocFirst%_%DocLast%.txt
				echo %OklahomaN% >> %Output%\Dr_%DocFirst%_%DocLast%.txt
				echo %OregonN% >> %Output%\Dr_%DocFirst%_%DocLast%.txt
				echo %PennsylvaniaN% >> %Output%\Dr_%DocFirst%_%DocLast%.txt
				echo %RhodeIslandN% >> %Output%\Dr_%DocFirst%_%DocLast%.txt
				echo %SouthCarolinaN%	>> %Output%\Dr_%DocFirst%_%DocLast%.txt	
				echo %SouthDakotaN% >> %Output%\Dr_%DocFirst%_%DocLast%.txt
				echo %TennesseeN% >> %Output%\Dr_%DocFirst%_%DocLast%.txt
				echo %TexasN%	>> %Output%\Dr_%DocFirst%_%DocLast%.txt
				echo %UtahN% >> %Output%\Dr_%DocFirst%_%DocLast%.txt
				echo %VirginiaN% >> %Output%\Dr_%DocFirst%_%DocLast%.txt
				echo %VermontN% >> %Output%\Dr_%DocFirst%_%DocLast%.txt
				echo %WashingtonN% >> %Output%\Dr_%DocFirst%_%DocLast%.txt
				echo %WisconsinN%	>> %Output%\Dr_%DocFirst%_%DocLast%.txt
				echo %WestVirginiaN% >> %Output%\Dr_%DocFirst%_%DocLast%.txt
				echo %WyomingN% >> %Output%\Dr_%DocFirst%_%DocLast%.txt
			
					echo. >> %Output%\Dr_%DocFirst%_%DocLast%.txt
					echo. >> %Output%\Dr_%DocFirst%_%DocLast%.txt
		echo -----------------Availability---------------------------------------------------------- >> %Output%\Dr_%DocFirst%_%DocLast%.txt
					echo. >> %Output%\Dr_%DocFirst%_%DocLast%.txt
					echo. >> %Output%\Dr_%DocFirst%_%DocLast%.txt
			echo - Dr. %DocLast% is unavailable for during assignment dates but does have availability for future consideration>> %Output%\Dr_%DocFirst%_%DocLast%.txt
					echo. >> %Output%\Dr_%DocFirst%_%DocLast%.txt

			echo - Dr. %DocLast% is available during assignment dates as well as for future consideration >> %Output%\Dr_%DocFirst%_%DocLast%.txt
					echo. >> %Output%\Dr_%DocFirst%_%DocLast%.txt
			 
			echo - Dr. %DocLast% is available ___ weeks per month, starting ________ for future consideration >> %Output%\Dr_%DocFirst%_%DocLast%.txt
					echo. >> %Output%\Dr_%DocFirst%_%DocLast%.txt

			echo - Dr. %DocLast% is currently on a long term locum assignment in ________, concluding _________, 2015 >> %Output%\Dr_%DocFirst%_%DocLast%.txt
					echo. >> %Output%\Dr_%DocFirst%_%DocLast%.txt

			echo - Dr. %DocLast% is extremely flexible working Locum Tenens until he/she finds a permanent position>> %Output%\Dr_%DocFirst%_%DocLast%.txt
					echo. >> %Output%\Dr_%DocFirst%_%DocLast%.txt
					echo. >> %Output%\Dr_%DocFirst%_%DocLast%.txt
		echo -----------------Expenses---------------------------------------------------------- >> %Output%\Dr_%DocFirst%_%DocLast%.txt
					echo. >> %Output%\Dr_%DocFirst%_%DocLast%.txt
					echo. >> %Output%\Dr_%DocFirst%_%DocLast%.txt
			echo **NOTE: Dr. %DocLast% will be driving their own vehicle** >> %Output%\Dr_%DocFirst%_%DocLast%.txt
				echo. >> %Output%\Dr_%DocFirst%_%DocLast%.txt
			echo Physician will drive own vehicle and be reimbursed for mileage according to the IRS mileage rate while on assignment>> %Output%\Dr_%DocFirst%_%DocLast%.txt
					echo. >> %Output%\Dr_%DocFirst%_%DocLast%.txt
					
			echo **NOTE: Any overtime requires prior approval** >> %Output%\Dr_%DocFirst%_%DocLast%.txt
				echo. >> %Output%\Dr_%DocFirst%_%DocLast%.txt
			echo Prior approval required>> %Output%\Dr_%DocFirst%_%DocLast%.txt
					echo. >> %Output%\Dr_%DocFirst%_%DocLast%.txt
					
			echo **NOTE: Call information below** >> %Output%\Dr_%DocFirst%_%DocLast%.txt
			echo. >> %Output%\Dr_%DocFirst%_%DocLast%.txt
			echo 	Pager Fee: Mon/Tue/Wed/Thur/Fri, if applicable>> %Output%\Dr_%DocFirst%_%DocLast%.txt
						echo. >> %Output%\Dr_%DocFirst%_%DocLast%.txt
			echo 	Weekend Call: Sat/Sun, if applicable>> %Output%\Dr_%DocFirst%_%DocLast%.txt
						echo. >> %Output%\Dr_%DocFirst%_%DocLast%.txt
			echo.
	
Rem completes file and informs you it has ben placed on desktop
	cls
	echo File has been placed %Output%
	pause

