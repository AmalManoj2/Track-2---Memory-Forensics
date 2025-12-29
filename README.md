I started by understanding the basics of rooting an Android phone. This included learning what rooting
actually does, how it grants superuser access, and how it bypasses many of Android’s built-in security
mechanisms. Along with this, I learned why backing up a phone is a critical step before attempting to root it,
as the process can result in data loss, boot loops, or even permanently bricked devices if something goes
wrong.

Next, I studied the general steps involved in rooting a device. These steps included installing Android Debug
Bridge (ADB) and the correct USB drivers, enabling OEM unlocking, unlocking the bootloader, flashing or
patching the boot image specific to the phone’s build number, and finally verifying whether we successfully
got root access. Before actually attempting rooting, I wanted to better understand the process and how it
relates to the scenarios provided in the task, especially from a security and forensic perspective.

As part of this preparation, I learned what a factory reset actually does and how Android handles encryption. I
focused on the two main types of encryption used on Android devices: Full Disk Encryption (FDE) and File-
Based Encryption (FBE). I learned how FDE encrypts the entire data partition as a single unit, while FBE
encrypts individual files using separate keys, allowing better security and flexibility. I also studied the change
from FDE to FBE and how this change affects data access, security, and forensic investigations. I also learned a
bit about concepts such as flashing firmware and patching boot images, and how these interact with
Android’s verified boot process.

After completing this research, I attempted to root a spare phone borrowed from my brother, an OPPO A9
2020. I created the necessary backups, enabled OEM unlocking, and was ready to fastboot. However, fastboot
didn't work at all. Initially, I assumed that I made a mistake in the process, so I carefully repeated each step.
When the issue remained, I decided to check whether this specific phone model would even allow me to root
it.

I had known that Google Pixel and OnePlus were good for rooting, but I wasn't aware about OPPO. So, I
found out that the phone I had was among the least "root-friendly" phones I could possibly have. I explored
other rooting methods, but most were either unreliable, extremely risky, or simply did not work for this model.
To avoid the risk of permanently damaging the phone, I decided to stop the rooting attempt at that stage.

I then looked deeper into why OPPO phones were notorious for being difficult to root. I found out that
fastboot access was either limited or disabled, flashing a boot image had a high chance of not working or
causing boot loops, and just finding the supported files or patches was difficult for certain models. Some
newer OPPO devices apparently include eFuses that can detect unauthorized modifications and blow a fuse
causing permanent physical damage.

Finally, I continued understanding how Android encrypts files internally and how file recovery techniques
work. This helped me understand where digital forensics fits into the provided scenarios, including how
rooting, factory resets, and encryption states impact evidence recovery. I also got a better idea of the forensic
tools used in such situations and the challenges posed by modern Android security mechanisms.

Overall, this task helped me develop both practical and theoretical knowledge of Android rooting, encryption,
and device security. Even though I was unable to successfully root my OPPO phone, the process itself was a
valuable learning experience. It highlighted the importance of understanding device-specific restrictions,
modern security protections, and the trade-offs between accessibility and data protection, especially in the
context of digital forensics.
