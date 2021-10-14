Role Name
=========

Deploys tahoe-lafs from pip2.7

License
-------

WTFPL

Minimal variable definition
----------

	tahoe:
		node:
			nickname: mynickname
			reveal_ip_address: "true"
			tub_port: 1234
			host: 1.2.3.4
		client:
		storage:
			enabled: "true"
			reserved_space: 3G
			expire_enabled: "true"
			expire_mode : age
			expire_override_lease_duration : 1 month
		helper:
		sftp:
			enabled: "false"

		introducers:
			testgrid: "pb://fodk4doc64febdoxke3a4ddfyanz7ajd@tcp:testgrid.tahoe-lafs.org:5000/el4fo3rm2h22cnilukmjqzyopdgqxrd2"

