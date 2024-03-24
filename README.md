Account: 

- Namada: tnam1qpywx9mx3ah2pkp7jdgkyth9605kxczpqqs90z39, tnam1qzcmw94c878a7phd2vqsjfltl69wd06zd5wn097t (account tnam1…z39 created account tnam1…97t, account tnam1…97t created IBC channel)
- Osmosis: osmo1ecltxd39lpykwm4q8lu8tzh08npjxwf8fj9yd0
- MEMO: tpknam1qq426f87jxhjkfqsh3aw2v54nqu9fcfxax65u8mwwfvjkundlgp5k4494k4

Create Channel: 

```powershell
2024-03-24T01:00:12.111460Z  INFO ThreadId(01) 🥂 shielded-expedition.88f17d1d14 => OpenAckConnection(OpenAck { Attributes { connection_id: connection-1622, client_id: 07-tendermint-3256, counterparty_connection_id: connection-2795, counterparty_client_id: 07-tendermint-3091 } }) at height 0-209934
2024-03-24T01:00:25.418201Z  INFO ThreadId(01) 🥂 osmo-test-5 => OpenConfirmConnection(OpenConfirm { Attributes { connection_id: connection-2795, client_id: 07-tendermint-3091, counterparty_connection_id: connection-1622, counterparty_client_id: 07-tendermint-3256 } }) at height 5-6210964
2024-03-24T01:00:28.421739Z  INFO ThreadId(01) connection handshake already finished for Connection { delay_period: 0ns, a_side: ConnectionSide { chain: BaseChainHandle { chain_id: shielded-expedition.88f17d1d14 }, client_id: 07-tendermint-3256, connection_id: connection-1622 }, b_side: ConnectionSide { chain: BaseChainHandle { chain_id: osmo-test-5 }, client_id: 07-tendermint-3091, connection_id: connection-2795 } }
2024-03-24T01:00:44.477732Z  INFO ThreadId(01) 🎊  shielded-expedition.88f17d1d14 => OpenInitChannel(OpenInit { port_id: transfer, channel_id: channel-1050, connection_id: None, counterparty_port_id: transfer, counterparty_channel_id: None }) at height 0-209937
2024-03-24T01:00:57.731084Z  INFO ThreadId(01) 🎊  osmo-test-5 => OpenTryChannel(OpenTry { port_id: transfer, channel_id: channel-6620, connection_id: connection-2795, counterparty_port_id: transfer, counterparty_channel_id: channel-1050 }) at height 5-6210972
2024-03-24T01:01:16.687864Z  INFO ThreadId(01) 🎊  shielded-expedition.88f17d1d14 => OpenAckChannel(OpenAck { port_id: transfer, channel_id: channel-1050, connection_id: connection-1622, counterparty_port_id: transfer, counterparty_channel_id: channel-6620 }) at height 0-209940
2024-03-24T01:01:29.702779Z  INFO ThreadId(01) 🎊  osmo-test-5 => OpenConfirmChannel(OpenConfirm { port_id: transfer, channel_id: channel-6620, connection_id: connection-2795, counterparty_port_id: transfer, counterparty_channel_id: channel-1050 }) at height 5-6210980
2024-03-24T01:01:32.705249Z  INFO ThreadId(01) channel handshake already finished for Channel { ordering: ORDER_UNORDERED, a_side: ChannelSide { chain: BaseChainHandle { chain_id: shielded-expedition.88f17d1d14 }, client_id: 07-tendermint-3256, connection_id: connection-1622, port_id: transfer, channel_id: channel-1050, version: None }, b_side: ChannelSide { chain: BaseChainHandle { chain_id: osmo-test-5 }, client_id: 07-tendermint-3091, connection_id: connection-2795, port_id: transfer, channel_id: channel-6620, version: None }, connection_delay: 0ns }
SUCCESS Channel {
    ordering: Unordered,
    a_side: ChannelSide {
        chain: BaseChainHandle {
            chain_id: ChainId {
                id: "shielded-expedition.88f17d1d14",
                version: 0,
            },
            runtime_sender: Sender { .. },
        },
        client_id: ClientId(
            "07-tendermint-3256",
        ),
        connection_id: ConnectionId(
            "connection-1622",
        ),
        port_id: PortId(
            "transfer",
        ),
        channel_id: Some(
            ChannelId(
                "channel-1050",
            ),
        ),
        version: None,
    },
    b_side: ChannelSide {
        chain: BaseChainHandle {
            chain_id: ChainId {
                id: "osmo-test-5",
                version: 5,
            },
            runtime_sender: Sender { .. },
        },
        client_id: ClientId(
            "07-tendermint-3091",
        ),
        connection_id: ConnectionId(
            "connection-2795",
        ),
        port_id: PortId(
            "transfer",
        ),
        channel_id: Some(
            ChannelId(
                "channel-6620",
            ),
        ),
        version: None,
    },
    connection_delay: 0ns,
}
```

Transactions: 

- To Osmosis: [https://www.mintscan.io/osmosis-testnet/tx/984EB530841E20F2E9A33D5DD03E4CC5C83AD5332DA320C00419D15A0ED9E00B?height=6211068](https://www.mintscan.io/osmosis-testnet/tx/984EB530841E20F2E9A33D5DD03E4CC5C83AD5332DA320C00419D15A0ED9E00B?height=6211068)
- Osmosis to Namada: [https://testnet.osmosis.explorers.guru/transaction/8D8957CC3C79C5E365993F374700AA3F057E0B78BD9E8419E6ACA472BC9B504C](https://testnet.osmosis.explorers.guru/transaction/8D8957CC3C79C5E365993F374700AA3F057E0B78BD9E8419E6ACA472BC9B504C)
- To Osmosis: [https://testnet.osmosis.explorers.guru/transaction/DC1EFEDE49167B366799D8E4AAFAEAF60C2502A7750F94D7E5686E192DFB753B](https://testnet.osmosis.explorers.guru/transaction/DC1EFEDE49167B366799D8E4AAFAEAF60C2502A7750F94D7E5686E192DFB753B)
- Osmosis to Namada: [https://testnet.osmosis.explorers.guru/transaction/6C14F442C72C2A6EE4B164D0145CB0810C388A70B76C652E2B0168A5030A849D](https://testnet.osmosis.explorers.guru/transaction/6C14F442C72C2A6EE4B164D0145CB0810C388A70B76C652E2B0168A5030A849D)
