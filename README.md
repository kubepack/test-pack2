# test-pack2 (edit file from both _vendor folder and local fodler)

`
$ pack pull # pull dependencies from manifest.yaml file
`

`
$ pack edit -s ./_vendor/github.com/a8uhnf/test-yml1/nginx-deployment.yaml  # edit file from _vendor/ folder 
`



`
$ pack edit -s ./nginx-deployment.yaml  # edit file from local folder 
`


`
$ pack up # generate combined yaml in _outlook/ folder. This uses src yaml and patch yaml 
`
