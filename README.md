# Gaming And Video Streaming Traffic for 5G (GAViST5G) Research

This project provides Python notebooks for enhancing CSV files generated from Wireshark PCAP captures detailed in the 5G Data Collection Steps PDF. The code processes network traffic data by enriching it with additional insights such as IP geolocation details, filtering background traffic and adding round-trip time (RTT), user geolocation, and connection type. Additionally, there is a notebook to aggregate packet data per second if desired. The order of processing the files is as follows:

1. 5G_Data_Collection_Steps
2. AddIPDetails
3. FilterGames/FilterVideo/FilterYouTube
4. AddPingGame/AddPingVideo
5. AnonymizeUserGeo
6. AddConnectionGame/AddConnectionVideo
7. OPTIONAL: AggregateBySecond

   
