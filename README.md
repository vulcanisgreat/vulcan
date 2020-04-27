## Vulcan Suite
This repository contains all the app used for the experiment of the state-aware testing tool. The repository includes the following:
 * **[attacker](attacker)**. Attacker based on *Intent* injection campaigns. The project is used to determine the minimum working set needed to trigger system reboots on Wear OS. The following experiments can be :
   * Rate. The rate to collect data from the sensors installed on the *smartwatch*.
   * Inter-device communication. Communication between both paired devices, *mobile* and *smartwatch*.
 * **[defender-poc](defender-poc)**. Proof-Of-Concept defender mechanism. The project implement a security mechanism based on a intermediate buffer for *Intents*. This mechanism helps to minimize system reboots due to similar attacker like the previous project.
 * **[ua-test](ua-test)**. Toy app for the wearable used to measure the impact on the user experience of our PoC defender mechanism.
 * **[vulcan](vulcan)**. Vulcan Stateful Fuzzer.
