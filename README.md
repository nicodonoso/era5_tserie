# era5_tserie
Matlab function that takes an ERA5 reanalysis point and converts it into time series.

% función era5_tserie por Nico Donoso nicolasdonosocastro@gmail.com

% extrae serie de tiempo de la variable var (ej.var='t')
% desde el archivo netcdf nc_file (ej. nc_file =
% '/home/nico/Documents/cecs/reanalysis/era5/era5_olivares/olivares_era5_TPP_suba_1979_1982.nc')
% en el punto (lat_aws, lon_aws).
% 
%   Ejemplo de uso:
% [z.t,z.temp] = era5_tserie(lat,lon,'variable','/home/nico/path_to_file/era5_1979_1982.nc')
or
% [z.t,z.temp] = era5_tserie(-35.1776,-75.2167,'t','/home/nico/path_to_file/era5_1979_1982.nc')

