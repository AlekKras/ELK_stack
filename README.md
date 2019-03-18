# Setup

Start ELK:
```
docker-compose up
```
You can also use `-d` background mode.

Visit (http://localhost:5601)[http://localhost:5601]

Default ports:
- `5000` - logstash tcp input
- `9200` - elasticsearch http
- `9300` - elasticsearch TCP transport
- `5601` - Kibana
- `8200` - APM 
