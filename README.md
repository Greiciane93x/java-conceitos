# java-conceitos

public static void main(String[] args){

	__ao utilizarmos o método trim, removemos os espaços da String_ <br/> 
	>>String vazio = " "; 
	>>String outroVazio = vazio.trim(); 

	_o método contains verifica se uma String possui uma substring_ <br/>	
	>>System.out.println(vazio.contains("Alu")); 
	
	_o método isEmpty pergunta se a String está vazia. Recebemos como retorno<br/> 
	um valor booleano_<br/> 
	>>System.out.println(outroVazio.isEmpty()); 

	>>String nome = "Teste"; 
	_o método charAt() retorna o caracter que ocupa uma posição específica_<br/> 
	>>char c = nome.charAt(2); 
	>>System.out.println(c); 
	
	_podemos passar uma sequencia de caracteres e perguntar qual é a posição dessa 
	String dentro da cadeia de caracteres_ 
	>>int pos = nome.indexOf("es");
	_possibilita a criação de uma subString. Ou seja, é manipulada uma cadeia de caracter e é  
	retornada uma nova_<br/> 
	>>String sub = nome.substring(1); 
	>>System.out.printl(sub); 
	
	_determinamos qual é o tamanho de determinada String com length_<br/> 
	>>System.out.println(nome.length); 
	
	>>for(int i = 0; i < nome.length(); i++){
	>>	System.out.println(nome.charAt(i)); 
	>>}

	
}
