# Important-Files
Files which are important for debugging

# Frontend - yarn.lock
We have used a newer yarn.lock version in the hopes that everything runs smooth but it can cause a fatal error when not using the yarn.lock file that we have in the "frontend" folder. In case you get the error:
`
./node_modules/@metamask/utils/node_modules/superstruct/dist/index.mjs 46:43 Module parse failed: Unexpected token (46:43) You may need an appropriate loader to handle this file type.
`
you have to replaceyour yarn.lock file with the one in here. 

WIP 
