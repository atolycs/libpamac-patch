configure_file(
	input: 'org.manjaro.pamac.daemon.service.in',
	output: 'org.manjaro.pamac.daemon.service',
	configuration: conf,
	install: true,
	install_dir: join_paths(get_option('datadir'), 'dbus-1', 'system-services'),
)

install_data('org.manjaro.pamac.daemon.conf', install_dir: join_paths(get_option('sysconfdir'), 'dbus-1', 'system.d'))
