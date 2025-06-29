%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
ReplicationCode_BC:             DATABASE OUTLINE 
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
	* AQR_FactorAgg_R_Daily
	* AQR_FactorAgg_R_Monthly 
	* AQR_FactorR_Daily
	* AQR_FactorR_Monthly 
		- HML_D_AQR_Global_Equities_rm67_25 %CONTAINS_20COUNTRY_VARIABLES   
		- HML_FF_AQR_Global_Equities_rm67_25 %CONTAINS_20COUNTRY_VARIABLES   
		- SMD_AQR_Global_Equities_rm67_25_CLEAN	%CONTAINS_20COUNTRY_VARIABLES   
		- ME_AQR84m_25 %CONTAINS_20COUNTRY_VARIABLES   			
		- UMD_AQR_rm67_25 %CONTAINS_20COUNTRY_VARIABLES   
		/ Graphs_col
			- ME_graphs_by_20countries  
	* DM9_own_FactorR_Daily 
	* DM9_own_FactorR_Monthly


