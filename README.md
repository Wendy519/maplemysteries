# Aspen Discovery search params: 
- Keyword: /Search/Results?lookfor={Author}%20{Title}
- Advanced: /Search/Results?join=AND&bool0[]=AND&lookfor0[0]={title}&type0%5B0%5D=Title&lookfor0[1]={author}&type0[1]=Author&submit
- Series: /Union/Search?view=list&showCovers=on&lookfor={series+name}&searchIndex=Series&searchSource=local

# Bibliocommons search params:
- Keyword: v2/search?query={title}%20{author]&searchType=smart
- Advanced: /v2/search?custom_edit=false&query=(title:({title})%20AND%20contributor:({author})%20)&searchType=bl&suppress=true
- Series: /v2/search?query={series%20name}&searchType=series

# Vega Discover search params:
 - Keyword: /search?query={title}%20AND%20{author}&searchType=everything&pageSize=10&rapido=true
 - Series: /search?query={series%20name}&searchType=series&pageSiz
  
# For UK Libraries see:
 - https://github.com/LibrariesHacked

