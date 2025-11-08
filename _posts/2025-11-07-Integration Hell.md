# To Integrate or Not?

I have spent some time grappling with Seurat's Integrate Layers function (official documentation here: <href>https://satijalab.org/seurat/reference/integratelayers</href>). Interestingly,
Scanpy does not have an integration step - at least not in the way you would think - the same way that Seurat does with IntegrateLayers. 

Seurat primarily has four integration options, all of which can be slotted into a seurat layer reduction. These methods are CCAIntegration, Harmony Integration, JointPCA Integration, and RPCAIntegration. I wanted to really breakdown what these four types of "integration" are doing and compare  to common scanpy elements. Seurat CCAInteration <href>https://satijalab.org/seurat/reference/ccaintegration</href>)  
