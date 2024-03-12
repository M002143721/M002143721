{
  "outbounds": 
  [
    {
      "type": "wireguard",
      "tag": "Warp-IR",
      "local_address": [
        "172.16.0.2/32",
        "2606:4700:110:8031:2dd:b5b3:c83b:9788/128"
      ],
      "private_key": "MOd/"MOd/"Z08Qv8rf1LsZ43ARgKCwPT7yW1CbqeXV2dwlzEc="
      "server": "162.159.192.200",
      "server_port": 8742,
      "peer_public_key": "bmXOC+F1FxEMF9dyiK2H5/1SUtzH0JuVo51h2wPfgyo=",
      "reserved": [81,255,130]
      "mtu": 1280,
      "fake_packets": "5-10"
    },
    {
      "type": "wireguard",
      "tag": "Warp-Main",
      "detour": "Warp-IR",
      "local_address": [
        "172.16.0.2/32",
        "2606:4700:110:89b4:5ea0:7291:e0b3:d0d5/128"
      ],
      "private_key": "CCC/TQTc82ub9i8f37Rpix2v425Sv/mxTzvE/iKRMkw=",
      "server": "162.159.192.200",
      "server_port": 8742,
      "peer_public_key": "bmXOC+F1FxEMF9dyiK2H5/1SUtzH0JuVo51h2wPfgyo=",
      "reserved": [252,23,174]
      "mtu": 1280,
      "fake_packets": "5-10"
    }
  ]
}
