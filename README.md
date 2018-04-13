# hello-world
Hi there let's try some C#

byte CalculateByteColor(byte color)
{
  int tempCol = (int)color;
  tempCol += 55;
  if(tempCol >= 256)
  {
    tempCol -= 256;
  }
  color = (byte)tempCol;
  return color;
}
