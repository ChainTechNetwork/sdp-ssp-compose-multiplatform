# SDP-SSP-Compose-Multiplatform

A scalable size unit for Compose Multiplatform for Android & iOS App

## Installation

Add the dependency to your `build.gradle.kts` file:

```
commonMain.dependencies {
    implementation("network.chaintech:sdp-ssp-compose-multiplatform:1.0.1")
}
```

## Usage

```kotlin
@Composable
fun App() = AppTheme {
    Box(
        modifier = Modifier
            .statusBarsPadding()
            .fillMaxSize()
            .background(Color.White),
        contentAlignment = Alignment.Center
    ) {
        Card(
            modifier = Modifier.fillMaxWidth(0.82f),
            shape = RoundedCornerShape(16.sdp),
            colors = CardDefaults.cardColors(Color(0xFFFBF3E8)),
        ) {
            Column(
                modifier = Modifier.fillMaxWidth(),
                horizontalAlignment = Alignment.CenterHorizontally,
            ) {
                Column(
                    modifier = Modifier
                        .fillMaxWidth()
                        .background(Color(0xFF585DDB))
                        .padding(vertical = 16.sdp),
                    horizontalAlignment = Alignment.CenterHorizontally,
                ) {
                    Image(
                        modifier = Modifier
                            .size(80.sdp),
                        painter = painterResource(Res.drawable.ic_user),
                        contentDescription = null,
                        contentScale = ContentScale.FillBounds
                    )

                    Text(
                        text = "Emily Dounger",
                        fontSize = 16.ssp,
                        color = Color.White,
                        fontWeight = FontWeight.Bold,
                        modifier = Modifier.padding(top = 12.sdp)
                    )
                }

                Text(
                    text = "Hi there \uD83D\uDC4B , We are Boards to share initital Goals and ideas.",
                    fontSize = 14.ssp,
                    textAlign = TextAlign.Center,
                    color = Color.Black,
                    lineHeight = 18.ssp,
                    fontWeight = FontWeight.Bold,
                    modifier = Modifier.padding(top = 30.sdp).padding(horizontal = 20.sdp)
                )

                Button(
                    onClick = {},
                    colors = ButtonDefaults.buttonColors(Color(0xFF007AFF)),
                    modifier = Modifier.padding(top = 24.sdp, bottom = 20.sdp)
                        .padding(horizontal = 20.sdp).fillMaxWidth().height(40.sdp)
                ) {
                    Text(text = "Say Hello", fontSize = 16.ssp)
                }
            }
        }
    }
}
```

## Android
- with using dp

- with using sdp

## iOS
- with using dp

- with using sdp


- For More Follow This Class -> [App.kt](www.google.com)

- Follow Medium Link for example -> [App.kt](www.google.com)

- Follow LinkedIn For More Updates -> [Mobile Innovation Network](https://www.linkedin.com/showcase/mobile-innovation-network)

