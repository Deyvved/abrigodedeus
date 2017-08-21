Dsout.createDimension (dname, len (the_dim) se  não the_dim.isunlimited () else  None )
18	
19	dx = 360,0 / nlon
20	Imprimir  ' ler / escrever lats '
21	Varin = modis.variables [ ' lat ' ]
22	OutVar = dsout.createVariable ( ' lat ' , varin.datatype, varin.dimensions)
...	
26	Imprimir  ' ler lons '
27	lons         = modis.variables [ ' lon ' ]
28	OutVar_lons = dsout.createVariable ( ' lon ' , lons.datatype, lons.dimensions)
