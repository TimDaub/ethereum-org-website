---
title: Docking della rete principale con Eth2
description: Scopri di più sul docking, ovvero il momento in cui la rete principale Ethereum si unirà al sistema proof of stake coordinato della beacon chain.
lang: it
template: eth2
sidebar: true
image: ../../../../../assets/eth2/merge.png
summaryPoints:
  [
    "L'attuale rete principale Ethereum sarà alla fine agganciata con il resto degli aggiornamenti Eth2.",
    'Il docking fonderà la rete principale "Eth1" con la beacon chain Eth2 e il sistema di sharding.',
    "Questo segnerà la fine del proof of work per Ethereum e completerà la transizione al proof of stake.",
    'Questa fase viene detta anche "Fase 1.5" nelle roadmap tecniche.',
  ]
---

<UpgradeStatus date="~Q1/Q2 2022">
    Questo aggiornamento seguirà l'arrivo delle shard chain. Ma è il momento in cui la <a href="/eth2/vision/">vision Eth2</a> si realizza pienamente: maggiore scalabilità, sicurezza e sostenibilità con lo staking a supporto di tutta la rete.
</UpgradeStatus>

## Che cos'è il docking? {#what-is-the-docking}

È importante ricordare che inizialmente gli altri aggiornamenti Eth2 vengono rilasciati separatamente dalla [rete principale](/glossary/#mainnet), cioè la catena che usiamo oggi. Il funzionamento della rete principale Ethereum continuerà ad essere assicurato dal [proof of work](/developers/docs/consensus-mechanisms/pow/), anche mentre la [beacon chain](/eth2/beacon-chain/) e le sue [shard chain](/eth2/shard-chains/) funzioneranno in parallelo utilizzando il [proof of stake](/developers/docs/consensus-mechanisms/pos/). Per docking si intende il momento in cui questi due sistemi si fonderanno.

Immagina Ethereum come una nave spaziale che non è ancora pronta per un viaggio interstellare. Con la beacon chain e le shard chain la community ha costruito un nuovo motore e uno scafo più resistente. Quando sarà il momento, l'attuale navicella aggancerà questo nuovo sistema diventando un'unica astronave, pronta a percorrere diversi anni luce e conquistare l'universo.

## Docking della rete principale {#docking-mainnet}

Quando sarà pronta, la rete principale Ethereum sarà "agganciata" (docking) dalla beacon chain, diventando uno shard che utilizza proof of stake anziché [proof of work](/developers/docs/consensus-mechanisms/pow/).

La rete principale aggiungerà la capacità di eseguire smart contract nel sistema di proof of stake, oltre a tutta la storia e allo stato corrente di Ethereum, per consentire consentendo una transizione senza intoppi per gli utenti e i possessori di ETH.

<!-- ### Improving Mainnet

Before Mainnet docks with the new eth2 system, it’s probably worthwhile sorting some of the issues that are in flight – often referred to as Ethereum1.x.

These include Improvements for

- **End users**: like [EIP-1559](https://eips.ethereum.org/EIPS/eip-1559) which changes the way users bid for blockspace. In other words, making transaction fees more efficient for end users.
- **Client runners**: making running clients more sustainable by capping disk space requirements.
- **Developers**: upgrading the EVM to be more flexible.

Plus many more.

[More on Ethereum1.x](/learn/#eth-1x)

These improvements all have a place in Eth2 so it’s likely that their progress may affect the timing of the docking. -->

## Dopo il docking {#after-the-docking}

Questo segnerà la fine del proof of work per Ethereum e inizierà l'era di una rete Ethereum più sostenibile ed ecologica. A questo punto Ethereum avrà la scalabilità, la sicurezza e la sostenibilità delineati nella [vision Eth2](/eth2/vision/).

## Relazione tra gli aggiornamenti {#relationship-between-upgrades}

Gli aggiornamenti Eth2 sono in qualche modo correlati. Quindi ricapitoliamo come il docking è correlato agli altri aggiornamenti.

### Docking e beacon chain {#docking-and-beacon-chain}

Una volta avvenuto il docking, saranno assegnati utenti che fanno staking, per convalidare la rete principale Ethereum. Proprio come con le shard chain. [Il mining](/developers/docs/consensus-mechanisms/pow/mining/) non sarà più necessario e chi se ne occupava potrà investire i propri guadagni nello staking nel nuovo sistema proof of stake.

<ButtonLink to="/eth2/beacon-chain/">La beacon chain</ButtonLink>

### Docking e shard chain {#docking-and-shard-chains}

Quando la rete principale diventerà uno shard, la riuscita dell'implementazione delle shard chain sarà fondamentale per questo aggiornamento. È probabile che la transizione svolgerà un ruolo importante nell'aiutare la community a decidere se distribuire un secondo aggiornamento per lo sharding. Questo aggiornamento renderà gli altri shard come la rete principale: saranno in grado di gestire transazioni e smart contract e non solo di fornire più dati.

<ButtonLink to="/eth2/shard-chains/">Shard chain</ButtonLink>
