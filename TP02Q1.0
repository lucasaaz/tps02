import java.io.BufferedReader;
import java.io.FileReader;
import java.util.Date;

class Filme{
   private String nome;
   private String tituloOriginal;
   private Date dataDeLancamento;
   private int duracao;
   private String genero;
   private String idiomaOriginal;
   private String situacao;
   private float orcamento;
   private String[] palavrasChave = new String[1000];
   
   public Filme(){
      
   }
   
   //remover Tags
   public String removerTags (String original) {
	   String resp = "";
	   for(int i=0; i<original.length(); i++) {
		   if(original.charAt(i)=='<') {
			   while(original.charAt(i)!='>')i++;{
				   
			   }   
		   }
	   }
	   return resp;
   }
   
   //ler
   public void ler(String nomeFilme)  throws Exception {
	   String caminho = "/temp/filmes/";
	   FileReader fr = new FileReader(caminho + nomeFilme);
	   BufferedReader br = new BufferedReader (fr);
	   
	   String linha = br.readLine();
	   while(linha.contains("Titulo Original")) {
	   linha = br.readLine();   
	   }
	  
	   
   }
   
   //clonagem
   public Filme clone() {
	   Filme clonagem = new Filme();
	   
	   setNome(nome);
	   setTituloOriginal(tituloOriginal);
	   setDataDeLancamento(dataDeLancamento);
	   setDuracao(duracao);
	   setGenero(genero);
	   setIdiomaOriginal(idiomaOriginal);
	   setSituacao(situacao);
	   setOrcamento(orcamento);
	   setPalavrasChave(palavrasChave);
	   
	   return clonagem;
   }

   
   //get set NOME
   public String getNome(){
      return nome;
   }
   public void setNome (String nome){
      this.nome = nome;
   }
   //get set Titulo Original
   public String getTituloOriginal(){
      return tituloOriginal;
   }
   public void setTituloOriginal(String tituloOriginal){
      this.tituloOriginal = tituloOriginal;
   }
   //get set Data De Lancamento
   public Date getDataDeLancamento(){
      return dataDeLancamento; 
   }
   public void setDataDeLancamento(Date dataDeLancamento){
      this.dataDeLancamento = dataDeLancamento;
   }
   //get set Duracao
   public int getDuracao(){
      return duracao;
   }   
   public void setDuracao(int duracao){
      this.duracao = duracao;
   }
   //get set Genero
   public String getGenero(){
      return genero;
   }   
   public void setGenero(String genero){
      this.genero = genero;
   }
   //get set Idioma Original
   public String getIdiomaOriginal(){
      return idiomaOriginal;
   }   
   public void setIdiomaOriginal(String idiomaOriginal){
      this.idiomaOriginal = idiomaOriginal;
   }
   //get set Situacao
   public String getSituacao(){
      return situacao;
   }
   public void setSituacao(String situacao){
      this.situacao = situacao;
   }
   //get set Orcamento   
   public float getOrcamento(){
      return orcamento;
   }
   public void setOrcamento(float orcamento){
      this.orcamento = orcamento;
   }
   //get set Orcamento 
   public String[] getPalavrasChave() {
	  return palavrasChave;
   }
   public void setPalavrasChave(String[] palavrasChave) {
	  this.palavrasChave = palavrasChave;
   }
 

}
