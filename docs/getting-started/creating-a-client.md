# Creating a client
Seeing as Coffeecord supports both Java and Kotlin, we provide examples for both below.
!!! note "Token"
    Please make sure you change any text stating "token" to your bot's token.
!!! note "Kotlin DSL"
    We have a more in-depth article on our Kotlin DSL [here](../kotlin-dsl/base.md).

=== "Java"
    ```java linenums="1"
    package com.example.bot;

    import xyz.deftu.coffeecord.*;

    public class ExampleBot {

        public static void main(String[] args) {
            DiscordClient client = new DiscordClient();
            client.login("token");
        }

    }
    ```

=== "Kotlin"
    ```kotlin linenums="1"
    package com.example.bot

    import xyz.deftu.coffeecord.*

    fun main() {
        val client = discord {
            token = "token"
        }

        client.login()
    }
    ```