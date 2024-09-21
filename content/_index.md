+++
title = "IoT Security"
description = "This project, IoT Hacking 101, aims to provide a comprehensive understanding of IoT security and the potential threats that exist."
+++

{{< lead >}}
This project, IoT Hacking 101, aims to provide a comprehensive understanding of IoT security and the potential threats that exist.
{{< /lead >}}


## Technologies
<div class="row py-3 mb-5">
	<div class="col-md-4">
		<div class="card flex-row border-0">
			<div class="mt-3">
				<span class="fas fa-tachometer-alt fa-2x text-primary"></span>
			</div>
			<div class="card-body pl-2">
				<h5 class="card-title">
					Bluetooth Security
				</h5>
				<p class="card-text text-muted">
					Learn about Bluetooth security risks and how to protect your devices from hacking. Discover best practices for securing your Bluetooth connections.
				</p>
			</div>
		</div>
	</div>
	<div class="col-md-4">
		<div class="card flex-row border-0">
			<div class="mt-3">
				<span class="fas fa-paint-brush fa-2x text-primary"></span>
			</div>
			<div class="card-body pl-2">
				<h5 class="card-title">
					Wi-fi Security
				</h5>
				<p class="card-text text-muted">
					Learn how to protect your Wi-Fi network from hackers. Discover the best security practices and tools to keep your data safe.
				</p>
			</div>
		</div>
	</div>
	<div class="col-md-4">
		<div class="card flex-row border-0">
			<div class="mt-3">
				<span class="fas fa-project-diagram fa-2x text-primary"></span>
			</div>
			<div class="card-body pl-2">
				<h5 class="card-title">
					LoRA Security
				</h5>
				<p class="card-text text-muted">
					Hugo does not require Java, Python or Ruby and is available as a simple binary or through NPM and other package managers.
				</p>
			</div>
		</div>
	</div>
	<div class="col-md-4">
		<div class="card flex-row border-0">
			<div class="mt-3">
				<span class="fas fa-cogs fa-2x text-primary"></span>
			</div>
			<div class="card-body pl-2">
				<h5 class="card-title">
					ZigBee Security
				</h5>
				<p class="card-text text-muted">
					Learn about ZigBee security vulnerabilities and best practices for protecting your IoT devices. Discover encryption methods and mitigation strategies.
				</p>
			</div>
		</div>
	</div>
	<div class="col-md-4">
		<div class="card flex-row border-0">
			<div class="mt-3">
				<span class="fas fa-search fa-2x text-primary"></span>
			</div>
			<div class="card-body pl-2">
				<h5 class="card-title">
					NB-IOT Security
				</h5>
				<p class="card-text text-muted">
					Easily find the content you look for through the search function.
				</p>
			</div>
		</div>
	</div>
	<div class="col-md-4">
		<div class="card flex-row border-0">
			<div class="mt-3">
				<span class="fas fa-code fa-2x text-primary"></span>
			</div>
			<div class="card-body pl-2">
				<h5 class="card-title">
					RFID / NFC Security
				</h5>
				<p class="card-text text-muted">
					Explore the security landscape of GSM networks, including common vulnerabilities, best practices for protection, and strategies to safeguard your data.
				</p>
			</div>
		</div>
	</div>

</div>

## OWASP IoT Top 10 2018


<img src="/images/OWASP-IoT-Top-10-2018-final.jpg"></img>


### I1 Weak, Guessable, or Hardcoded Passwords	
Use of easily bruteforced, publicly available, or unchangeable credentials, including backdoors in firmware or client software that grants unauthorized access to deployed systems.
### I2 Insecure Network Services	
Unneeded or insecure network services running on the device itself, especially those exposed to the internet, that compromise the confidentiality, integrity/authenticity, or availability of information or allow unauthorized remote control.
### I3 Insecure Ecosystem Interfaces	
Insecure web, backend API, cloud, or mobile interfaces in the ecosystem outside of the device that allows compromise of the device or its related components. Common issues include a lack of authentication/authorization, lacking or weak encryption, and a lack of input and output filtering.
### I4 Lack of Secure Update Mechanism	
Lack of ability to securely update the device. This includes lack of firmware validation on device, lack of secure delivery (un-encrypted in transit), lack of anti-rollback mechanisms, and lack of notifications of security changes due to updates.
### I5 Use of Insecure or Outdated Components	
Use of deprecated or insecure software components/libraries that could allow the device to be compromised. This includes insecure customization of operating system platforms, and the use of third-party software or hardware components from a compromised supply chain
### I6 Insufficient Privacy Protection	
User’s personal information stored on the device or in the ecosystem that is used insecurely, improperly, or without permission.
### I7 Insecure Data Transfer and Storage	
Lack of encryption or access control of sensitive data anywhere within the ecosystem, including at rest, in transit, or during processing
### I8 Lack of Device Management	
Lack of security support on devices deployed in production, including asset management, update management, secure decommissioning, systems monitoring, and response capabilities.
### I9 Insecure Default Settings	
Devices or systems shipped with insecure default settings or lack the ability to make the system more secure by restricting operators from modifying configurations.
### I10 Lack of Physical Hardening	
Lack of physical hardening measures, allowing potential attackers to gain sensitive information that can help in a future remote attack or take local control of the device.