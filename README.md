# Documents, Fields and Descriptions

Fields and Masks
-
- Date DD/MM/YYYY
- Time HH:MM:SS
- Date and Time DD/MM/YYYY HH:MM:SS
- Money R$ 999.999,99 (2 decimals, decimal symbol "," and thounsand symbol ".")
- Weight 9,999kg (kilograns, 3 decimals for grams)
- Distance/Speed in Kilometers and meters

People Documents
-
- RG = General Registry number, mask 99.999.999-X
- CPF = Unique People Number, mask 999.999.999-99

Company Documents
-
- CNPJ = Unique Company Number, mask 999.999.999-99
- IE/Inscrição Estadual = State Subscription number, mask 999.999.999-99
- IM/Inscrição Municipal = City Subscription number, no mask, each city implements

# Brazilian Digital Documents

Documents is digital emited in a process monitored by a Goverment Department named SEFAZ.

The comunication between SEFAZ and the company who is emiting an Invoice requires valid digital certificates from companies, and there are some type of documents what a company can emit based on company business, all documents are XML files with a schema defined by SEFAZ and signed by the company who is emiting.

The most common is the Invoice, that we local named as NF/Nota Fiscal/NF-e, every company can emit NF, but for some other particular business there are other documents needed for example CT-e and MDF-e are documents related to the transport business.

CT-e document resume costs details for the invoices that will be transported.

MDF-e document consolidate the CT-es travel details like driver, vehicle, other documents, when start and finish these travel.

NEED EXPLANATION ABOUT OTHER THINGS??? Place an Issue!
