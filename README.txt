Bijgeleverde CSV documenten volgen volgende kolomstructuur.

## Test Structuur

 - ID: ID van de gevoerde test. Referentie naar de parameterlijst. ID '0' komt in ieder bestand overeen met dezelfde parameter waarden voor de test.
 - index: Iedere test is 50 maal uitgevoerd. Iedere iteratie van die test met gespecifieerde 'ID' krijgt een andere index.

## Test Parameters

 - voices: het aantal stemmen dat afgespeeld wordt.
 - voiceToEQandComp: het aantal stemmen dat aan een Equalizer en Compressor geconnecteerd wordt.
 - effects: het aantal effecten op één track.
 - voicesToEffects: het aantal stemmen dat aan een stramien van effecten geconnecteerd wordt.

## Test Resultaten

 - CPUPerc: percentage CPU-gebruik van een iteratie van de test.
 - MemPerc: percentage geheugengebruik van een iteratie van de test.

