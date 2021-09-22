 protected override void OnConfiguring(DbContextOptionsBuilder optionsBuilder)
        {
           optionsBuilder.UseSqlServer(@"Data Source = TUNC\SQLEXPRESS; Initial Catalog = MVCOrderCustomer; User Id = sa1; Password = cts12345; Integrated Security = False; ");
                 base.OnConfiguring(optionsBuilder);
        }
