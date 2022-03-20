# Wikibase manifests

This GitHub repository stores manifests of some public Wikibase instances.

By entering a manifest in OpenRefine's Wikibase selection dialog window (`Select Wikibase instance...` in the Wikidata/Wikibase extension menu), you can start (batch) editing that particular Wikibase.

![image](https://user-images.githubusercontent.com/9881645/159169440-db7b6aa5-783b-4909-bb17-ed7b1f4fd4e7.png)<br>
Click the `Add Wikibase` button to add the manifest's URL (preferred) or json.

See [OpenRefine's documentation](https://docs.openrefine.org/next/manual/wikibase/configuration#for-wikibase-end-users) for some additional information.

| Wikibase                                   | Manifest                                   |
| ------------------------------------------ | ------------------------------------------ |
| https://www.wikidata.org                   | [wikidata-manifest.json](https://raw.githubusercontent.com/OpenRefine/wikibase-manifests/master/wikidata-manifest.json)                 |
| https://artbase.rhizome.org                | [rhizome-artbase-manifest.json](https://raw.githubusercontent.com/OpenRefine/wikibase-manifests/master/rhizome-artbase-manifest.json)          |
| https://or-wikibase-test.wiki.opencura.com | [openrefine-wikibase-test-manifest.json](https://raw.githubusercontent.com/OpenRefine/wikibase-manifests/master/openrefine-wikibase-test-manifest.json) |
| https://data.biblissima.fr | [biblissima-data-manifest.json](https://raw.githubusercontent.com/OpenRefine/wikibase-manifests/master/biblissima-data-manifest.json)
| https://commons.wikimedia.org *(manifest v2, needs OpenRefine 3.6+)* | [wikimedia-commons-manifest.json](https://github.com/OpenRefine/wikibase-manifests/blob/master/wikimedia-commons-manifest.json)

# Version 1 and 2 manifests

Manifests following the version 2 syntax, such as the [Wikimedia Commons manifest](https://github.com/OpenRefine/wikibase-manifests/blob/master/wikimedia-commons-manifest.json), only are supported in OpenRefine 3.6 onwards, *not* in older versions of OpenRefine.

# Write and add your own

You can write manifests for other Wikibase instances according to [this tutorial](https://github.com/OpenRefine/OpenRefine/wiki/Write-a-Wikibase-manifest) and make them discoverable by sending a PR here. Also feel free to add them to the table above 😎
