# Gaming And Video Streaming Traffic for 5G (GAViST5G) Research

This project provides Python notebooks for enhancing CSV files generated from Wireshark PCAP captures. The code processes network traffic data by enriching it with additional insights such as IP geolocation details, filtering background traffic and adding round-trip time (RTT), user geolocation, and connection type. Additionally, there is a notebook to aggregate packet data per second if desired. The order of processing the files is as follows:

1. AddIPDetails
2. FilterGames/FilterVideo/FilterYouTube
3. AddPingGame/AddPingVideo
4. AnonymizeUserGeo
5. AddConnectionGame/AddConnectionVideo
6. OPTIONAL: AggregateBySecond

   
