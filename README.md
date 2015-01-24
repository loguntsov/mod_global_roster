mod_global_roster
=================

Compile

make all

Create symlink from this directory to the ebin directory of ejabberd.

%% Add module to ejabberd.yml
```
	mod_global_roster:
		key: roster
		redist_host: "0.0.0.0"
		redis_port: 6379
		redis_db: 0
```

%% Versions

%% Erlang >= OTP_R14A (eredis needs the binary module which seems to have been introduced in this version)

%% Ejabberd tested with 2.1.x but may work on others
