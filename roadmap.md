---> server is just a software..

# programming lang used in backend -- java, js , php, c++ (with this we are gonna use a framework also )

js framework -- mongoose(used for databases) , express(used in routing)

# lang used in database -- mongo, mySql , postgres, sqlite (and here we are gonna use ORM / ODM )

# ---- A js runtime ---- NodeJs / Deno / Bun

how does backend work ???
==================================================
# humare pass database (mysql, mongodb, ) hota h jo ki ek system pr hoga, or humare pass backend m (functions) honge, frontend se ye sb functions aate h, backend check krega ki kya ye content sahi h? agr sahi h toh response bhj do nhi h agr sahi toh response bhj do.. (jo bhi response hoga vo api format m bhjte h)

frontend <-----> api <----> backend <----> db (another continent)


# NOTE - backend multiple systems pr deploy kiya ja skta h 
# NOTE - database humesha dusre continents m hota h..

javascript based backend -------------->
==================================================

# yaha pr sirf 3 scenarios honge :-

# 1. ya toh hum directlt data handle krnge (koi data aaya username/ password/ object / string)
# 2. ya fir hum file handle krnge  (koi file aayi jaise photos/ videos)
# 3. ya fir third party (API) handle krnge 

file structure
==================================================

# all the work is done in source (src) directory.

file names---- 
==================================================

# index file is the entry point -- connect db
# app file --- (config, cookie, urlencode)
# constants --- (enums, db-name)

directory structure ----
==================================================

# db directory -- actual code jo db s connect hoga
# models --- data rkhne k liye uska schema/ structure
# controllers --- saari functionalities controllers m likhe jate h 
# routes --- sari routes (links kaise hogi / kasie nhi hogi ) ye sb yaha define hota h
# middlewares 
# utils --- utilities
# More (depends)
