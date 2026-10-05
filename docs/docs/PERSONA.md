Synthetic user

Ana, 32 years old works alone on Sundays at a small civil help desk in Mexico City. She reads slowly, distrusts apps, and gives up silently when confused. She has 12 open cases and one new one just arrived. She is not a lawyer, not a bank employee, and not a police officer. She supports navigation, and the decisions belong to the institutions.

Task given to the persona

Open the live URL, register a new breach case from start to finish, and decide the priority and the next steps for the coordinator to take.

Where the persona hesitated or got lost

On the first screen, Ana asked: "Do I have to know if the device is safe before I even talk to the person? What if the person does not know?" She wanted a short explanation of what "safe device" means.

On the priority screen, Ana asked: "Urgent, standard, routine — who decided this? Can I change it?" She wanted to be able to override the priority when her judgment said otherwise.

On the export screen, Ana asked: "Does this save on the phone or on the site? If the phone is the problem, where does the packet go?" She was not sure whether the packet was stored somewhere else.

On the checklist screen, Ana asked: "What if the person is in another state and the Fiscalía route is different?" She wanted to know if the tool works outside Mexico City.

What I fixed

Added a short inline explanation under the safe-device question: "A safe device is one that is not in the hands of the attacker." This removed the first confusion.

Added a small "Change priority" button next to the priority level, so the coordinator can override the automatic classification.

Added one line to the export screen: "The packet downloads on this device. It is not uploaded to any server."

Added a small note under the checklist: "Referral routes may change by state. Confirm the local route before sending the person."

What I did not fix (documented)

Real referral routes to Fiscalías and CONDUSEF change by state. The prototype uses fictional routes labeled as simulated.

The tool cannot verify whether the device is actually safe. It only guides the coordinator.

The tool does not store cases on a server. This is by design, but it means the coordinator must keep her own notes outside the tool.

Conclusion

The persona test showed that the MVP is simple enough for the coordinator to use during a live call, and that the two main risks are trust in the automatic priority and confusion about where the packet is stored. Both were addressed with small inline changes. The tool does not replace the coordinator's judgment, and it does not replace the institutions. It gives the coordinator one honest first-hour plan without storing personal data.

