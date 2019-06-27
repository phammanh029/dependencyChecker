# dependencyChecker
A tool for check missing dlls file for windows application ( c++, c#).

This tool using visual studio development tool ( dumpbin.exe and link.exe). so if you are install visual studio, by default. it will work normally. If not, please copy link.exe and dumpbin.exe file to your binary folder (contain mk.dependent-walker.exe file)

# build
 - open project by visual studio
 - build
  

# usage
mk.dependent-walker.exe [moule_file]");
                Console.WriteLine("Usage2: mk.dependent-walker.exe [folder] native : print all native dll in [folder] directory");
                Console.WriteLine("Usage3: mk.dependent-walker.exe [folder] order : print order of all dll in [folder] directory ");
