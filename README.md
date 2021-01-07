# petoneer_revogi_py

Usage:

pet = Petoneer();

pet.auth("<<EMAIL>>", "<<PASSWORD>>")

fountain = pet.get_device_details("<<SERIAL_NO>>")

pprint(fountain)

devices = pet.get_registered_devices()

pprint(devices)
