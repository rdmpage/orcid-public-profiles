ORCID public profiles
=====================

Paglione, Laura, Peters, Robert, Oyler, Catalina, Simpson, Will, Montenegro, Angel, Ramírez Monge, José Francisco, Bryant, Rebecca, et al. (2013). ORCID Annual Public Data File, 2013. ORCID. [doi:10.14454/07243.2013.001](http://dx.doi.org/10.14454/07243.2013.001)

Extract all files from tarball (takes several hours on my early 2011 MacBook Pro)

    tar -xvf public_profiles.tar

Get a single ORCID file from the tarball

    tar -xvf public_profiles.tar ./json/0000-0003-4816-2909.json

To get a list of all the files in the tar ball (so we can easily search for an ORCID ID):

    tar -tvf public_profiles.tar > files.txt

