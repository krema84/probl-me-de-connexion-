# probl-me-de-connexion-
[12:15:24.496] [1] [ Info] [Eco] >>> START EcoServer, Version=1.0.0.0, Culture=neutral, PublicKeyToken=null  [12:15:24.520] [1] [ Info] [Eco] Eco Server 0.8.3.3 beta   [12:15:24.585] [1] [ Info] [Eco] Server Initialization...   [12:15:24.585] [1] [ Info] [Eco] Starting LocalizationPlugin...   [12:15:24.932] [1] [ Info] [Eco] Starting ModKitPlugin...   [12:15:24.932] [1] [ Info] [Eco] Loading mods...   [12:15:25.018] [1] [ Info] [Eco] Compiling mods...   [12:15:26.070] [1] [ Info] [Eco] Loading Eco.IntegrationTests...   [12:15:26.076] [1] [ Info] [Eco] Loading mods finished in 1,142.8ms   [12:15:26.076] [1] [ Info] [Eco] Starting NetworkManager...   [12:15:26.076] [5] [ Info] [Eco] Initializing Simulation Types...   [12:15:26.168] [38] [ Info] [Eco] Starting BackupPlugin...   [12:15:26.168] [40] [ Info] [Eco] Starting WorldGeneratorPlugin...   [12:15:26.168] [42] [ Info] [Eco] Starting GameplayStatsPlugin...   [12:15:26.200] [38] [ Info] [Eco] Starting StorageManager...   [12:15:26.648] [5] [ Info] [Eco] Initializing items...   [12:15:29.530] [38] [ Info] [Eco] Starting PausePlugin...   [12:15:29.547] [38] [ Info] [Eco] Loading Pause...   [12:15:31.098] [5] [ Info] [Eco] Initializing skills...   [12:15:31.176] [38] [ Info] [Eco] Starting StatDatabase...   [12:15:31.176] [35] [ Info] [Eco] Starting WorldPlugin...   [12:15:31.232] [35] [ Info] [Eco] Loading World...   [12:15:34.654] [35] [ Info] [Eco] Initializing world...   [12:15:35.818] [35] [ Info] [Eco] Starting TimePlugin...   [12:15:35.818] [35] [ Info] [Eco] Loading Time...   [12:15:35.818] [35] [ Info] [Eco] Starting ReputationPlugin...   [12:15:35.818] [35] [ Info] [Eco] Loading Reputation...   [12:15:35.834] [35] [ Info] [Eco] Starting PlayerHousingManager...   [12:15:35.834] [35] [ Info] [Eco] Starting UserManager...   [12:15:35.895] [35] [ Info] [Eco] Loading Users...   [12:15:36.197] [35] [ Info] [Eco] Initializing inventories...   [12:15:36.228] [35] [ Info] [Eco] Starting EcoObjectManager...   [12:15:36.228] [35] [ Info] [Eco] Loading Objects...   [12:15:36.459] [1] [ Info] [Eco] Server Initialization finished in 11,874.1ms   [12:15:36.459] [1] [ Info] [Eco] Failed to load server, Exception was Exception: JsonReaderException Message:Invalid character after parsing property name. Expected ':' but got: ". Path 'WaterLevel', line 9, position 2. Source:Newtonsoft.Json  Newtonsoft.Json.JsonReaderException: Invalid character after parsing property name. Expected ':' but got: ". Path 'WaterLevel', line 9, position 2.    at Newtonsoft.Json.JsonTextReader.ParseProperty()    at Newtonsoft.Json.Serialization.JsonSerializerInternalReader.PopulateObject(Object newObject, JsonReader reader, JsonObjectContract contract, JsonProperty member, String id)    at Newtonsoft.Json.Serialization.JsonSerializerInternalReader.Populate(JsonReader reader, Object target)    at Newtonsoft.Json.JsonSerializer.PopulateInternal(JsonReader reader, Object target)    at Newtonsoft.Json.JsonConvert.PopulateObject(String value, Object target, JsonSerializerSettings settings)    at Eco.Core.Plugins.PluginConfig`1.Load(String filename)    at Eco.WorldGenerator.WorldGeneratorPlugin..ctor()  
