# assignment-4
All answers to assignments or where they are located in the code, can be found in the Answers.md file.


## Notes and commands for future reference
For at loade forskellige filer ind i F# interactive skal man bruge nedenstående kommand, ikke den som er angivet i exercises i bogen.
```bash
dotnet fsi -r *jeres path til det her*/fsharp/FsLexYacc.Runtime.dll Absyn.fs ExprPar.fs ExprLex.fs Expr.fs Parse.fs 

dotnet fsi -r /mnt/c/Users/mchrn/ITU/5_Semester/Programs_as_data/fsharp/FsLexYacc.Runtime.dll Absyn.fs FunPar.fs FunLex.fs Parse.fs Fun.fs ParseAndRun.fs