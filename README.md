# matlab-mysql
This repository simply contains compiled MySQL files from:
https://www.mathworks.com/matlabcentral/fileexchange/8663-mysql-database-connector


To run, simply copy/paste the appropriate mex & dll files to the desired folder location.

Make sure that the folder is available to Matlab: `addpath` or set the folder as a default path.

To test:
`mysql('status')` will return `Not connected`
