struct carte 
{
  char nume_carte[20],editura[20];
  int anul[4],nr_exemplare;
  public:
  void add(),editare(),stergere();
  int disponibila();
  }
  
  struct persoane
  {
  char nume[20],cnp[13];
  public:
  void add(),editare(),stergere();
  int nr_total,nr_maxim;
  }
  
