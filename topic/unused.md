!SLIDE bullets

# Kibana Monitoring in ES 6

(http://ec2-34-203-252-37.compute-1.amazonaws.com:5601)

Not working in AWS instance - need to do more research on this

!SLIDE bullets

# Using ES Debug mode

* Undocumented debug mode for Elasticsearch
* Append `?debug=1` to queries
* Need to 

~~~SECTION:notes~~~

```bash
curl -u esadmin:Passw0rd! http://ec2-34-203-252-37.compute-1.amazonaws.com:9200/ptportalregistry_psftdb_orcl_es_alias/_search?debug=1 -XPOST -H "SearchUser: PS" -H 'Content-Type: application/json'
```
~~~ENDSECTION~~~