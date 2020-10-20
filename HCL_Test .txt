import scala.collection.immutable._
    
object GFG 
{    
    def main(args:Array[String])  
    {  
  
      printlist(List(1,2,3,4,5,6,7,8,9,10))
      calculateArea(10,20)
          
    } 
  
    def printlist(datalist:List[Integer]):Unit={
    for(element<-datalist)  
        {  
            println(element)  
        }
  }
  
  def calculateArea(height:Int, base:Int):Unit={
    val area = (height*base)/2
    println("Area :"+area)
  }
}