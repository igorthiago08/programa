{

                            Online Pascal Compiler.
                Code, Compile, Run and Debug Pascal program online.
Write your code in this editor and press "Run" button to execute it.

}


program calculo_media;
var
n1, n2, n3, media: real;

begin
  writeln ('digite a primeira nota');
  readln(n1);
  writeln('digite a segunda nota');
  readln(n2);
  writeln('digite a terceira nota');
  readln(n3);
  media:= (n1+n2+n3)/3;
  writeln(' sua media é ', media:4:2);
end.
