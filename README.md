# New_Coolify
2026-03-23T18:17:56.348Z Error en la conexion con la Base: MongooseServerSelectionError: connect ECONNREFUSED 127.0.0.1:27017
2026-03-23T18:17:56.348Z at _handleConnectionErrors (/usr/src/app/node_modules/mongoose/lib/connection.js:1169:11)
2026-03-23T18:17:56.348Z at NativeConnection.openUri (/usr/src/app/node_modules/mongoose/lib/connection.js:1100:11)
2026-03-23T18:17:56.348Z at async main (file:///usr/src/app/server.js:13:9) {
2026-03-23T18:17:56.348Z errorLabelSet: Set(0) {},
2026-03-23T18:17:56.348Z reason: TopologyDescription {
2026-03-23T18:17:56.348Z type: 'Unknown',
2026-03-23T18:17:56.348Z servers: Map(1) { 'localhost:27017' => [ServerDescription] },
2026-03-23T18:17:56.348Z stale: false,
2026-03-23T18:17:56.348Z compatible: true,
2026-03-23T18:17:56.348Z heartbeatFrequencyMS: 10000,
2026-03-23T18:17:56.348Z localThresholdMS: 15,
2026-03-23T18:17:56.348Z setName: null,
2026-03-23T18:17:56.348Z maxElectionId: null,
2026-03-23T18:17:56.348Z maxSetVersion: null,
2026-03-23T18:17:56.348Z commonWireVersion: 0,
2026-03-23T18:17:56.348Z logicalSessionTimeoutMinutes: null
2026-03-23T18:17:56.348Z },
2026-03-23T18:17:56.348Z code: undefined,
2026-03-23T18:17:56.348Z cause: TopologyDescription {
2026-03-23T18:17:56.348Z type: 'Unknown',
2026-03-23T18:17:56.348Z servers: Map(1) { 'localhost:27017' => [ServerDescription] },
2026-03-23T18:17:56.348Z stale: false,
2026-03-23T18:17:56.348Z compatible: true,
2026-03-23T18:17:56.348Z heartbeatFrequencyMS: 10000,
2026-03-23T18:17:56.348Z localThresholdMS: 15,
2026-03-23T18:17:56.348Z setName: null,
2026-03-23T18:17:56.348Z maxElectionId: null,
2026-03-23T18:17:56.348Z maxSetVersion: null,
2026-03-23T18:17:56.349Z commonWireVersion: 0,
2026-03-23T18:17:56.349Z logicalSessionTimeoutMinutes: null
2026-03-23T18:17:56.349Z }
2026-03-23T18:17:56.349Z }
