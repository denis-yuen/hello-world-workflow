Usage 
===

    dockstore dev tool2csv --entry quay.io/collaboratory/hello-world-workflow > params.csv
    gvim params.csv
    dockstore dev launch --entry quay.io/collaboratory/hello-world-workflow --csv params.csv
