# sem-visitor

vou ter um produto qu tem preço frete e acrescimo

package semvisitor;


public class Produto {
   
    private String nome;
    private final float preco;
    private float valorFrete;
    private float acrescimo;
    
    public Produto(String nome, float preco, float valorFrete, float acrescimo) {
        this.nome = nome;
        this.preco = preco;
        this.valorFrete = valorFrete;
        this.acrescimo = acrescimo;
    }

    public float getValorLoja(){
        return this.preco;
    }
  public float getValorTelefone(){
      return this.preco + this.valorFrete;
  }
    public float getValorSite(){
        return this.preco + this.valorFrete + this.acrescimo;
    }
    public static void main(String[] args) {
  
        
    }
    
    e outra classe
    
    package semvisitor;


public class SemVisitor {

    
    public static void main(String[] args) {
    
    }
    
}

    

