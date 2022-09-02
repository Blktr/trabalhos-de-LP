using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace aula_1__3ºbimestre_
{
    class Program
    {
        static void Main(string[] args)
        {

            int opcao;
            int opcaocompra;
            double dinheiro = 900;


            do
            {
                Console.Clear();
                Console.WriteLine("menu de compras cs");
                Console.WriteLine("1-pistolas");
                Console.WriteLine("2-pesada");
                Console.WriteLine("3-SMG");
                Console.WriteLine("4-rifles");
                Console.WriteLine("5-equipamentos");
                Console.WriteLine("6-granadas");
                Console.WriteLine("7-sair");

                opcao = Convert.ToInt32(Console.ReadLine());

                if (opcao == 1)
                {
                    Console.Clear();
                    Console.WriteLine("você selecionou a opcao menu de pistolas do CS");
                    Console.WriteLine("1- USP------------------------------------$200");
                    Console.WriteLine("2- P152-----------------------------------$250");
                    Console.WriteLine("3- CZ75-----------------------------------$500");
                    Console.WriteLine("4- Barettas-------------------------------$300");
                    Console.WriteLine("5- Fiver-seven----------------------------$500");
                    Console.WriteLine("6- Deagle---------------------------------$700");

                    opcaocompra = Convert.ToInt32(Console.ReadLine());

                    if (opcaocompra == 1)
                    {
                        if (dinheiro >= 200)
                        {
                            Console.WriteLine("voce adquiriu uma USP por $200");
                            dinheiro = dinheiro - 200;
                            Console.ReadKey();
                        }
                        else
                        {
                            Console.WriteLine("voce não tem dinheiro o suficiente para comprar este item");
                            Console.ReadKey();

                        }
                    }

                    else if (opcaocompra == 2)
                    {
                        if (dinheiro >= 250)
                        {
                            Console.WriteLine("voce adquiriu uma P152 por $250");
                            dinheiro -= 250;
                            Console.ReadKey();
                        }

                        else
                        {
                            Console.WriteLine("voce não tem dinheiro o suficiente para comprar este item");
                            Console.ReadKey();
                        }
                    }
                    if (opcaocompra == 4)
                    {
                        if (dinheiro >= 300)
                        {
                            Console.WriteLine("voce adquiriu uma barettas por $300");
                            dinheiro = dinheiro - 300;
                            Console.ReadKey();
                        }
                        else
                        {
                            Console.WriteLine("voce não tem dinheiro o suficiente para comprar este item");
                            Console.ReadKey();

                        }

                    }
                    if (opcaocompra == 3)
                    {
                        if (dinheiro >= 500)
                        {
                            Console.WriteLine("voce adquiriu uma CZ75 por $500");
                            dinheiro = dinheiro - 500;
                            Console.ReadKey();
                        }
                        else
                        {
                            Console.WriteLine("voce não tem dinheiro o suficiente para comprar este item");
                            Console.ReadKey();

                        }

                    }
                    if (opcaocompra == 5)
                    {
                        if (dinheiro >= 500)
                        {
                            Console.WriteLine("voce adquiriu uma fiver-seven por $500");
                            dinheiro = dinheiro - 500;
                            Console.ReadKey();
                        }
                        else
                        {
                            Console.WriteLine("voce não tem dinheiro o suficiente para comprar este item");
                            Console.ReadKey();

                        }

                    }
                    if (opcaocompra == 6)
                    {
                        if (dinheiro >= 500)
                        {
                            Console.WriteLine("voce adquiriu uma deagle por $700");
                            dinheiro = dinheiro - 700;
                            Console.ReadKey();
                        }
                        else
                        {
                            Console.WriteLine("voce não tem dinheiro o suficiente para comprar este item");
                            Console.ReadKey();

                        }

                    }


                    Console.ReadKey();
                }


                if (opcao == 2)
                {
                    Console.Clear();
                    Console.WriteLine("você selecionou a opcao menu de armas presadas do CS");
                    Console.WriteLine("1- xm1014------------------------------------2200$");
                    Console.WriteLine("2- mag-7-------------------------------------$1800");
                    Console.WriteLine("3- Sawed-Off	--------------------------------$1200");
                    Console.WriteLine("4- Nova--------------------------------------$1200");
                    Console.WriteLine("5- M249--------------------------------------$5200");
                    Console.WriteLine("6- Negev-------------------------------------$1700");

                    opcaocompra = Convert.ToInt32(Console.ReadLine());

                    if (opcaocompra == 1)
                    {
                        if (dinheiro >= 2200)
                        {
                            Console.WriteLine("voce adquiriu uma xm1014 por $2200");
                            dinheiro = dinheiro - 2200;
                            Console.ReadKey();
                        }
                        else
                        {
                            Console.WriteLine("voce não tem dinheiro o suficiente para comprar este item");
                            Console.ReadKey();

                        }
                    }

                    else if (opcaocompra == 2)
                    {
                        if (dinheiro >= 1800)
                        {
                            Console.WriteLine("voce adquiriu uma mag-7 por $1800");
                            dinheiro -= 1800;
                            Console.ReadKey();
                        }

                        else
                        {
                            Console.WriteLine("voce não tem dinheiro o suficiente para comprar este item");
                            Console.ReadKey();
                        }
                    }

                    else if (opcaocompra == 3)
                    {
                        if (dinheiro >= 1200)
                        {
                            Console.WriteLine("voce adquiriu uma Sawed-Off por $1200");
                            dinheiro -= 1200;
                            Console.ReadKey();
                        }

                        else
                        {
                            Console.WriteLine("voce não tem dinheiro o suficiente para comprar este item");
                            Console.ReadKey();
                        }
                    }
                    else if (opcaocompra == 4)
                    {
                        if (dinheiro >= 1200)
                        {
                            Console.WriteLine("voce adquiriu uma nova por $1200");
                            dinheiro -= 1200;
                            Console.ReadKey();
                        }

                        else
                        {
                            Console.WriteLine("voce não tem dinheiro o suficiente para comprar este item");
                            Console.ReadKey();
                        }
                    }
                    else if (opcaocompra == 5)
                    {
                        if (dinheiro >= 5200)
                        {
                            Console.WriteLine("voce adquiriu uma m249 por $5200");
                            dinheiro -= 5200;
                            Console.ReadKey();
                        }

                        else
                        {
                            Console.WriteLine("voce não tem dinheiro o suficiente para comprar este item");
                            Console.ReadKey();
                        }
                    }
                    if (opcaocompra == 6)
                    {
                        if (dinheiro >= 1700)
                        {
                            Console.WriteLine("voce adquiriu uma neveg por $1700");
                            dinheiro = dinheiro - 700;
                            Console.ReadKey();
                        }
                        else
                        {
                            Console.WriteLine("voce não tem dinheiro o suficiente para comprar este item");
                            Console.ReadKey();

                        }

                    }
                    Console.ReadKey();
                }






                if (opcao == 3)
                    {
             
                    Console.Clear();
                    Console.WriteLine("você selecionou a opcao menu de SMG do CS");
                    Console.WriteLine("1- MAC-10------------------------------------$1050");
                    Console.WriteLine("2- UMP-------------------------------------$1200");
                    Console.WriteLine("3- MP9--------------------------------$1250");
                    Console.WriteLine("4- Bizon--------------------------------------$1400");
                    Console.WriteLine("5- MP5--------------------------------------$1500");
                    Console.WriteLine("6- MP7-------------------------------------$1500");
                    Console.WriteLine("6- P90-------------------------------------$2350");
                    opcaocompra = Convert.ToInt32(Console.ReadLine());

                    if (opcaocompra == 1)
                        { 
                        if (dinheiro >= 1050)
                        {
                            Console.WriteLine("voce adquiriu uma MAC-10 por $1050");
                            dinheiro = dinheiro - 1050;
                            Console.ReadKey();
                        }
                        else
                        {
                            Console.WriteLine("voce não tem dinheiro o suficiente para comprar este item");
                            Console.ReadKey();

                        }
                    }

                 else   if (opcaocompra == 2)
                    {
                        if (dinheiro >= 1200)
                        {
                            Console.WriteLine("voce adquiriu uma UMP por $1200");
                            dinheiro = dinheiro - 1200;
                            Console.ReadKey();
                        }
                        else
                        {
                            Console.WriteLine("voce não tem dinheiro o suficiente para comprar este item");
                            Console.ReadKey();

                        }
                    }
                 else   if (opcaocompra == 3)
                    {
                        if (dinheiro >= 1250)
                        {
                            Console.WriteLine("voce adquiriu uma MP9 por $1250");
                            dinheiro = dinheiro - 1250;
                            Console.ReadKey();
                        }
                        else
                        {
                            Console.WriteLine("voce não tem dinheiro o suficiente para comprar este item");
                            Console.ReadKey();

                        }
                    }
           else         if (opcaocompra == 4)
                    {
                        if (dinheiro >= 1400)
                        {
                            Console.WriteLine("voce adquiriu uma Bizon por $1400");
                            dinheiro = dinheiro - 1400;
                            Console.ReadKey();
                        }
                        else
                        {
                            Console.WriteLine("voce não tem dinheiro o suficiente para comprar este item");
                            Console.ReadKey();

                        }
                    }
            else        if (opcaocompra == 5)
                    {
                        if (dinheiro >= 1500)
                        {
                            Console.WriteLine("voce adquiriu uma MP5 por $1500");
                            dinheiro = dinheiro - 1500;
                            Console.ReadKey();
                        }
                        else
                        {
                            Console.WriteLine("voce não tem dinheiro o suficiente para comprar este item");
                            Console.ReadKey();

                        }
                    }
                else    if (opcaocompra == 6)
                    {
                        if (dinheiro >= 1500)
                        {
                            Console.WriteLine("voce adquiriu uma MP7 por $1500");
                            dinheiro = dinheiro - 1500;
                            Console.ReadKey();
                        }
                        else
                        {
                            Console.WriteLine("voce não tem dinheiro o suficiente para comprar este item");
                            Console.ReadKey();

                        }
                    }

                    Console.ReadKey();

                }
                else if (opcao == 4)
                {
                    Console.Clear();
                    Console.WriteLine("você selecionou a opção menu de equipamentos do CS");
                    Console.ReadKey();

                }
                else if (opcao == 5)
                {
                    Console.Clear();
                    Console.WriteLine("você selecionou a opção menu de equipamentos do CS");
                    Console.ReadKey();

                }
                else if (opcao == 6)
                {
                    Console.Clear();
                    Console.WriteLine("você selecionou a opção menu de granadas do CS");
                    Console.ReadKey();

                }
                else if (opcao == 7)
                {
                    Console.Clear();
                    Console.WriteLine("você saiu do menu de escolhas do CS");
                    Console.ReadKey();

                }
                } 

                Console.ReadKey();
                } while (opcao != 7) ;
            }
            }
    }

