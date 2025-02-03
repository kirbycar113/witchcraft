commands for code:

createcmd USAGE:
createcmd <NAME>{
   (your code here)
}
end

runcmd USAGE:
runcmd {<NAME OF CMD>}
end

mm (movemouse) USAGE:

mm {120pxX, 240pxY}
end
or
mm movebyorigin {0pxX, 0pxY}
end

click USAGE:

click LMB
end
or
click RMB
end
or
click SCRLL <number between -100 and 100>
end

keyboard USAGE:

keyboard{a}
end
or
keyboard{a,z} (INPUTTED VIRTUALLY FROM LEFT TO RIGHT)
end
or
keyboard{ctr + a, ctr + c, deleteletter}
end

comment USAGE:
/. hello world ./

commands in interactive mode (ran directly):
help:
shows all available commands.

run:
runs a .wc file by the file path.

syntax:
NO capitals unless outside of a command parameter.
NO "end" before another command, example:

end
click RMB
runcmd {examplecommand}
end

NO comments inside a command parameter, example:
runcmd {/. example comment ./}
end

note from creator:
please, put an "end" at the end of a ".wc" script, or it will NOT run.