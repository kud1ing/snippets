# Download JARs and dependencies using `ivy`

* Download `ivy`.
* Execute `ivy -dependency <GROUP> <SOFTWARE> <VERSION> -retrieve "[artifact]-[revision](-[classifier]).[ext]"`.

Example:

`ivy -dependency org.apache.pdfbox pdfbox 2.0.6 -retrieve "[artifact]-[revision](-[classifier]).[ext]"`
