This data contains the predicted tropical Pacific SST anomalies from three hindcast experiments during the period 1982-2016.
The control run without any modification in CESM, the WWB run with parameterized WWBs and the Non_WWB run with spurious WWBs removed in the model.
  
Source: fc_SSTA.nc

dimensions:
	target_time = 420 ;
variables:
	float nino34_ssta_control(target_time) ;
		nino34_ssta_control:long_name = "Nino 3.4 SSTA predicted from the control run" ;
		nino34_ssta_control:_FillValue = 9.96921e+36f ;
	int target_time(target_time) ;
		target_time:units = "months since 1982-01-01 00:00:00" ;
	float nino34_ssta_wwb(target_time) ;
		nino34_ssta_wwb:long_name = "Nino 3.4 SSTA predicted from the WWB run" ;
		nino34_ssta_wwb:_FillValue = 9.96921e+36f ;
	float nino34_ssta_nonwwb(target_time) ;
		nino34_ssta_nonwwb:long_name = "Nino 3.4 SSTA predicted from the Non_WWB run" ;
		nino34_ssta_nonwwb:_FillValue = 9.96921e+36f ;
	float nino4_ssta_control(target_time) ;
		nino4_ssta_control:long_name = "Nino 4 SSTA predicted from the control run" ;
		nino4_ssta_control:_FillValue = 9.96921e+36f ;
	float nino4_ssta_wwb(target_time) ;
		nino4_ssta_wwb:long_name = "Nino 4 SSTA predicted from the WWB run" ;
		nino4_ssta_wwb:_FillValue = 9.96921e+36f ;
	float nino4_ssta_nonwwb(target_time) ;
		nino4_ssta_nonwwb:long_name = "Nino 4 SSTA predicted from the Non_WWB run" ;
		nino4_ssta_nonwwb:_FillValue = 9.96921e+36f ;
	float nino3_ssta_control(target_time) ;
		nino3_ssta_control:long_name = "Nino 3 SSTA predicted from the control run" ;
		nino3_ssta_control:_FillValue = 9.96921e+36f ;
	float nino3_ssta_wwb(target_time) ;
		nino3_ssta_wwb:long_name = "Nino 3 SSTA predicted from the WWB run" ;
		nino3_ssta_wwb:_FillValue = 9.96921e+36f ;
	float nino3_ssta_nonwwb(target_time) ;
		nino3_ssta_nonwwb:long_name = "Nino 3 SSTA predicted from the Non_WWB run" ;
		nino3_ssta_nonwwb:_FillValue = 9.96921e+36f ;
