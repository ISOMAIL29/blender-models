**TURKISH**

Blender'da bu mini-ATX anakartı yaparken, her bir parçanın temelini bir küp, düzlem ya da silindirle oluşturdum. 
Anakartın ana hatlarından RAM slotlarına, CPU soketine ve üzerindeki tüm küçük detaylara kadar her şeyi Extrude ve 
Scale komutlarıyla şekillendirdim. Özellikle RAM slotları gibi kırmızı bölgelerdeki ve çipset soğutucusundaki katmanlı 
görünümleri oluşturmak için Loop Cut'ı sıkça kullandım.

Parçaları doğru yerlerine yerleştirmek, onları anakart yüzeyinde veya birbirlerine göre konumlandırmak için Grab ve Move 
temel araçlarımdı. I/O panelindeki USB portları, ses girişleri ve Ethernet portu gibi hassas kesimler için bazen Boolean 
operasyonlarını kullandım, bazen de Extrude Manifold ile temiz delikler açtım. Daha spesifik, küçük detaylar veya belirli 
yüzeylerdeki ince kesikler için Knife Tool'u kullandım.

Modelime renk vermek için ise her bir parçaya ayrı bir Material atadım: anakartın yeşili, RAM slotlarındaki kırmızı ve USB 
portlarındaki mavi veya gri tonları gibi. Modelimde keskin hatlar ve net geometrik formlar istediğim için, Subdivision Surface 
modifikatörünü neredeyse hiç kullanmadım; bu modelleme tarzında sert yüzeyleri korumak önemliydi. Bevel'ı da sadece bazı 
köşelere hafif bir yumuşaklık katmak istediğimde kullandım, genel modelimde belirgin bir yuvarlaklık hedeflemiyordum. 

Kısacası, her şey temel geometrilerin manipülasyonuyla şekillendi.

**ENGLISH**

When modeling this mini-ATX motherboard in Blender, I primarily used Extrude and Scale to shape all components, from the main 
board to the RAM slots and CPU socket. Loop Cut was frequently employed for creating layered details, particularly on the red 
RAM slots and chipset heatsink.

For precise placement on the board, Grab and Move were essential. I utilized Boolean operations or Extrude Manifold for clean 
cuts like the I/O panel ports, and the Knife Tool for finer details on surfaces.

I assigned distinct Materials to each part to define their colors, such as the motherboard's green or the RAM slots' red. Given my aim 
for sharp, geometric forms, I sparingly used Bevel for slight edge softening and largely avoided the Subdivision Surface modifier. 
Ultimately, the entire model was crafted by manipulating basic geometries.
