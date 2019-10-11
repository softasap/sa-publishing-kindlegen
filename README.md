sa-publushing-kindlegen
=======================

[![Build Status](https://travis-ci.org/softasap/sa-publushing-kindlegen.svg?branch=master)](https://travis-ci.org/softasap/sa-publushing-kindlegen)


KindleGen is a command line tool used to build eBooks that can be sold through Amazon's Kindle platform. 
This tool is best for publishers and individuals who are familiar with HTML and want to convert their HTML, XHTML,
 XML (OPF/IDPF format), or ePub source into a Kindle Book


Simple:

```YAML


     - {
         role: "sa-publushing-kindlegen"
       }

```


Advanced:

```YAML


    - {
        role: "sa-publushing-kindlegen",
        kindlegen_version: "2.9",
        kindlegen_dir: "/opt/kindlegen"
      }

```


See box-example for standalone installation example


Usage with ansible galaxy workflow
----------------------------------

If you installed the sa-publushing-kindlegen  role using the command


`
   ansible galaxy install softasap.sa-publushing-kindlegen
`

the role will be available in the folder library/sa-publushing-kindlegen.

Please adjust the path accordingly.

```YAML

     - {
         role: "softasap.sa-publushing-kindlegen"
       }

```



Copyright and license
---------------------

Code is dual licensed under the [BSD 3 clause] (https://opensource.org/licenses/BSD-3-Clause) and the [MIT License] (http://opensource.org/licenses/MIT). Choose the one that suits you best.

Reach us:

Subscribe for roles updates at [FB] (https://www.facebook.com/SoftAsap/)

Join gitter discussion channel at [Gitter](https://gitter.im/softasap)

Discover other roles at  http://www.softasap.com/roles/registry_generated.html

visit our blog at http://www.softasap.com/blog/archive.html 
