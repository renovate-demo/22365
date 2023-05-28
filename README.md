## 22365

```json
"config": {
 "gradle": [
   {"packageFile": "settings.gradle.kts", "datasource": "maven", "deps": []},
   {"packageFile": "build.gradle.kts", "datasource": "maven", "deps": []},
   {
     "packageFile": "gradle/libs.versions.toml",
     "datasource": "maven",
     "deps": [
       {
         "depName": "com.squareup.okhttp3:okhttp",
         "groupName": "plainOkHttp",
         "currentValue": "4.9.0",
         "managerData": {
           "fileReplacePosition": 334,
           "packageFile": "gradle/libs.versions.toml"
         },
         "fileReplacePosition": 334,
         "datasource": "maven",
         "registryUrls": [
           "https://plugins.gradle.org/m2/",
           "https://repo.maven.apache.org/maven2"
         ],
         "depType": "dependencies",
         "updates": [
           {
             "bucket": "non-major",
             "newVersion": "4.11.0",
             "newValue": "4.11.0",
             "releaseTimestamp": "2023-04-23T01:33:43.000Z",
             "registryUrl": "https://plugins.gradle.org/m2",
             "newMajor": 4,
             "newMinor": 11,
             "updateType": "minor",
             "branchName": "renovate/plainokhttp"
           }
         ],
         "packageName": "com.squareup.okhttp3:okhttp",
         "warnings": [],
         "versioning": "gradle",
         "sourceUrl": "https://github.com/square/okhttp",
         "homepage": "https://square.github.io/okhttp/",
         "currentVersion": "4.9.0",
         "isSingleVersion": true,
         "fixedVersion": "4.9.0"
       },
       {
         "depName": "com.microsoft.sqlserver:mssql-jdbc",
         "groupName": "dash.official.mssql",
         "currentValue": "11.2.0.jre17",
         "managerData": {
           "fileReplacePosition": 368,
           "packageFile": "gradle/libs.versions.toml"
         },
         "fileReplacePosition": 368,
         "datasource": "maven",
         "registryUrls": [
           "https://plugins.gradle.org/m2/",
           "https://repo.maven.apache.org/maven2"
         ],
         "depType": "dependencies",
         "updates": [
           {
             "bucket": "non-major",
             "newVersion": "11.2.3.jre18",
             "newValue": "11.2.3.jre18",
             "releaseTimestamp": "2023-01-12T23:37:42.000Z",
             "registryUrl": "https://plugins.gradle.org/m2",
             "newMajor": 11,
             "newMinor": 2,
             "updateType": "patch",
             "branchName": "renovate/dash.official.mssql"
           },
           {
             "bucket": "major",
             "newVersion": "12.2.0.jre11",
             "newValue": "12.2.0.jre11",
             "releaseTimestamp": "2023-01-31T23:27:49.000Z",
             "registryUrl": "https://plugins.gradle.org/m2",
             "newMajor": 12,
             "newMinor": 2,
             "updateType": "major",
             "branchName": "renovate/major-dash.official.mssql"
           }
         ],
         "packageName": "com.microsoft.sqlserver:mssql-jdbc",
         "warnings": [],
         "versioning": "gradle",
         "sourceUrl": "https://github.com/Microsoft/mssql-jdbc",
         "currentVersion": "11.2.0.jre17",
         "isSingleVersion": true,
         "fixedVersion": "11.2.0.jre17"
       },
       {
         "depName": "org.slf4j:slf4j-api",
         "groupName": "mixed.sl.f4j.api",
         "currentValue": "1.7.35",
         "managerData": {
           "fileReplacePosition": 409,
           "packageFile": "gradle/libs.versions.toml"
         },
         "fileReplacePosition": 409,
         "datasource": "maven",
         "registryUrls": [
           "https://plugins.gradle.org/m2/",
           "https://repo.maven.apache.org/maven2"
         ],
         "depType": "dependencies",
         "updates": [
           {
             "bucket": "non-major",
             "newVersion": "1.7.36",
             "newValue": "1.7.36",
             "releaseTimestamp": "2022-02-08T13:33:51.000Z",
             "registryUrl": "https://plugins.gradle.org/m2",
             "newMajor": 1,
             "newMinor": 7,
             "updateType": "patch",
             "branchName": "renovate/mixed.sl.f4j.api"
           },
           {
             "bucket": "major",
             "newVersion": "2.0.7",
             "newValue": "2.0.7",
             "releaseTimestamp": "2023-03-17T19:36:59.000Z",
             "registryUrl": "https://plugins.gradle.org/m2",
             "newMajor": 2,
             "newMinor": 0,
             "updateType": "major",
             "branchName": "renovate/major-mixed.sl.f4j.api"
           }
         ],
         "packageName": "org.slf4j:slf4j-api",
         "warnings": [],
         "versioning": "gradle",
         "sourceUrl": "https://github.com/qos-ch/slf4j",
         "homepage": "http://www.slf4j.org",
         "currentVersion": "1.7.35",
         "isSingleVersion": true,
         "fixedVersion": "1.7.35"
       },
       {
         "depType": "plugin",
         "depName": "org.jetbrains.kotlin.plugin.serialization",
         "packageName": "org.jetbrains.kotlin.plugin.serialization:org.jetbrains.kotlin.plugin.serialization.gradle.plugin",
         "currentValue": "1.8.10",
         "managerData": {
           "fileReplacePosition": 444,
           "packageFile": "gradle/libs.versions.toml"
         },
         "groupName": "underscores.only.kotlin",
         "fileReplacePosition": 444,
         "datasource": "maven",
         "registryUrls": ["https://plugins.gradle.org/m2/"],
         "updates": [
           {
             "bucket": "non-major",
             "newVersion": "1.8.21",
             "newValue": "1.8.21",
             "releaseTimestamp": "2023-05-28T13:07:04.000Z",
             "newMajor": 1,
             "newMinor": 8,
             "updateType": "patch",
             "branchName": "renovate/underscores.only.kotlin"
           }
         ],
         "warnings": [],
         "versioning": "gradle",
         "registryUrl": "https://plugins.gradle.org/m2",
         "currentVersion": "1.8.10",
         "isSingleVersion": true,
         "fixedVersion": "1.8.10"
       }
     ]
   },
   {
     "packageFile": "src/main/kotlin/gradle.example.kotlin-application-conventions.gradle.kts",
     "datasource": "maven",
     "deps": []
   },
   {
     "packageFile": "src/main/kotlin/gradle.example.kotlin-common-conventions.gradle.kts",
     "datasource": "maven",
     "deps": [
       {
         "depName": "org.apache.commons:commons-text",
         "currentValue": "1.10.0",
         "managerData": {
           "fileReplacePosition": 488,
           "packageFile": "src/main/kotlin/gradle.example.kotlin-common-conventions.gradle.kts"
         },
         "fileReplacePosition": 488,
         "datasource": "maven",
         "registryUrls": [
           "https://plugins.gradle.org/m2/",
           "https://repo.maven.apache.org/maven2"
         ],
         "depType": "dependencies",
         "updates": [],
         "packageName": "org.apache.commons:commons-text",
         "warnings": [],
         "versioning": "gradle",
         "sourceUrl": "https://gitbox.apache.org/repos/asf?p=commons-text.git",
         "homepage": "https://commons.apache.org/proper/commons-text",
         "currentVersion": "1.10.0",
         "fixedVersion": "1.10.0"
       }
     ]
   },
   {
     "packageFile": "src/main/kotlin/gradle.example.kotlin-library-conventions.gradle.kts",
     "datasource": "maven",
     "deps": []
   }
 ],
 "gradle-wrapper": [
   {
     "deps": [
       {
         "depName": "gradle",
         "currentValue": "7.4",
         "replaceString": "https\\://services.gradle.org/distributions/gradle-7.4-bin.zip",
         "datasource": "gradle-version",
         "versioning": "gradle",
         "updates": [
           {
             "bucket": "non-major",
             "newVersion": "7.6.1",
             "newValue": "7.6.1",
             "releaseTimestamp": "2023-02-24T13:54:42.000Z",
             "newMajor": 7,
             "newMinor": 6,
             "updateType": "minor",
             "branchName": "renovate/gradle-7.x"
           },
           {
             "bucket": "major",
             "newVersion": "8.1.1",
             "newValue": "8.1.1",
             "releaseTimestamp": "2023-04-21T12:31:26.000Z",
             "newMajor": 8,
             "newMinor": 1,
             "updateType": "major",
             "branchName": "renovate/gradle-8.x"
           }
         ],
         "packageName": "gradle",
         "warnings": [],
         "sourceUrl": "https://github.com/gradle/gradle",
         "registryUrl": "https://services.gradle.org/versions/all",
         "homepage": "https://gradle.org",
         "currentVersion": "7.4",
         "isSingleVersion": true,
         "fixedVersion": "7.4"
       }
     ],
     "packageFile": "gradle/wrapper/gradle-wrapper.properties"
   }
 ]
}
```
