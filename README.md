# produto
public class Produto {
    private String nome;
    private double preco;
    private String caminhoImagem;

    // Construtor
    public Produto(String nome, double preco, String caminhoImagem) {
        this.nome = nome;
        this.preco = preco;
        this.caminhoImagem = caminhoImagem;
    }

    // Getters e Setters
    public String getNome() {
        return nome;
    }

    public void setNome(String nome) {
        this.nome = nome;
    }

    public double getPreco() {
        return preco;
    }

    public void setPreco(double preco) {
        this.preco = preco;
    }

    public String getCaminhoImagem() {
        return caminhoImagem;
    }

    public void setCaminhoImagem(String caminhoImagem) {
        this.caminhoImagem = caminhoImagem;
    }
    public class Produto {
    private String nome;
    private double preco;
    private String caminhoImagem;

    // Construtor
    public Produto(String nome, double preco, String caminhoImagem) {
        this.nome = nome;
        this.preco = preco;
        this.caminhoImagem = caminhoImagem;
    }

    // Getters e Setters
    public String getNome() {
        return nome;
    }

    public void setNome(String nome) {
        this.nome = nome;
    }

    public double getPreco() {
        return preco;
    }

    public void setPreco(double preco) {
        this.preco = preco;
    }

    public String getCaminhoImagem() {
        return caminhoImagem;
    }

    public void setCaminhoImagem(String caminhoImagem) {
        this.caminhoImagem = caminhoImagem;
    }
    
  package com.exemplo;

public class Main {
    public static void main(String[] args) {
        CadastroProduto cadastro = new CadastroProduto();

        Produto produto1 = new Produto("Produto 1", 10.0, "caminho/para/imagem1.jpg");
        Produto produto2 = new Produto("Produto 2", 20.0, "caminho/para/imagem2.jpg");

        cadastro.adicionarProduto(produto1);
        cadastro.adicionarProduto(produto2);

        for (Produto produto : cadastro.listarProdutos()) {
            System.out.println("Nome: " + produto.getNome());
            System.out.println("Preço: " + produto.getPreco());
            System.out.println("Caminho da Imagem: " + produto.getCaminhoImagem());
    }
  }
}
