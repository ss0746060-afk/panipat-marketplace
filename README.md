<!DOCTYPE html>
<html lang="hi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Panipat Marketplace - Buy & Sell Old Items</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
</head>
<body style="margin: 0; font-family: Arial, sans-serif; background-color: #f2f4f5; color: #002f34;">

    <!-- 1. टॉप हेडर -->
    <header style="background-color: #fff; padding: 10px 15px; box-shadow: 0 2px 4px rgba(0,0,0,0.1); position: sticky; top: 0; z-index: 100;">
        <div style="display: flex; justify-content: space-between; align-items: center; max-width: 1200px; margin: 0 auto;">
            <div style="font-size: 24px; font-weight: bold; color: #002f34; letter-spacing: 1px;">
                <i class="fa-solid fa-shop" style="color: #00bfb3;"></i> PANIPAT
            </div>
            <button style="background: #fff; border: 5px solid; border-image: linear-gradient(to right, #ffce32, #3a77ff, #23e5db) 1; padding: 5px 15px; font-weight: bold; border-radius: 20px; cursor: pointer; color: #002f34;">
                <i class="fa-solid fa-plus"></i> SELL
            </button>
        </div>
    </header>

    <!-- 2. सर्च बार -->
    <div style="background-color: #fff; padding: 15px; border-top: 1px solid #edeff0; text-align: center;">
        <div style="max-width: 600px; margin: 0 auto; display: flex; border: 2px solid #002f34; border-radius: 4px; overflow: hidden;">
            <input type="text" placeholder="Find Cars, Mobile Phones, Bedsheets and more..." style="flex: 1; padding: 12px; border: none; outline: none; font-size: 14px;">
            <button style="background-color: #002f34; border: none; padding: 0 20px; color: #fff; cursor: pointer;">
                <i class="fa-solid fa-magnifying-glass"></i>
            </button>
        </div>
    </div>

    <!-- 3. कैटेगरीज -->
    <div style="max-width: 1200px; margin: 20px auto; padding: 0 15px;">
        <h3 style="font-size: 18px; margin-bottom: 15px;">Browse Categories</h3>
        <div style="display: flex; gap: 10px; overflow-x: auto; padding-bottom: 10px; scrollbar-width: none;">
            <div style="background: white; padding: 10px 20px; border-radius: 4px; border: 1px solid #ccd5d6; white-space: nowrap; font-weight: bold; font-size: 14px;"><i class="fa-solid fa-mobile-screen-button"></i> Mobiles</div>
            <div style="background: white; padding: 10px 20px; border-radius: 4px; border: 1px solid #ccd5d6; white-space: nowrap; font-weight: bold; font-size: 14px;"><i class="fa-solid fa-car"></i> Cars</div>
            <div style="background: white; padding: 10px 20px; border-radius: 4px; border: 1px solid #ccd5d6; white-space: nowrap; font-weight: bold; font-size: 14px;"><i class="fa-solid fa-mattress-pillow"></i> Bedsheets</div>
            <div style="background: white; padding: 10px 20px; border-radius: 4px; border: 1px solid #ccd5d6; white-space: nowrap; font-weight: bold; font-size: 14px;"><i class="fa-solid fa-laptop"></i> Electronics</div>
        </div>
    </div>

    <!-- 4. सामानों की लिस्ट (अब असली फोटो के साथ) -->
    <main style="max-width: 1200px; margin: 0 auto; padding: 0 15px 40px 15px;">
        <h3 style="font-size: 18px; margin-bottom: 15px;">Fresh Recommendations</h3>
        
        <div style="display: grid; grid-template-columns: repeat(auto-fill, minmax(160px, 1fr)); gap: 15px;">
            
            <!-- आइटम 1: आईफोन -->
            <div style="background-color: #fff; border: 1px solid #ccd5d6; border-radius: 4px; overflow: hidden; position: relative;">
                <img src="https://images.unsplash.com/photo-1510557880182-3d4d3cba35a5?w=400" style="width: 100%; height: 140px; object-fit: cover;">
                <div style="padding: 10px;">
                    <div style="font-size: 18px; font-weight: bold; margin-bottom: 5px;">₹ 12,500</div>
                    <div style="font-size: 14px; color: #406367; white-space: nowrap; overflow: hidden; text-overflow: ellipsis;">iPhone 11 (128GB)</div>
                    <div style="font-size: 11px; color: #777; margin-top: 10px; display: flex; justify-content: space-between;">
                        <span>Model Town, Panipat</span>
                    </div>
                </div>
                <i class="fa-regular fa-heart" style="position: absolute; top: 10px; right: 10px; background: white; padding: 6px; border-radius: 50%; color: #002f34; box-shadow: 0 2px 4px rgba(0,0,0,0.1);"></i>
            </div>

            <!-- आइटम 2: बेडशीट -->
            <div style="background-color: #fff; border: 1px solid #ccd5d6; border-radius: 4px; overflow: hidden; position: relative;">
                <img src="https://images.unsplash.com/photo-1522771739844-6a9f6d5f14af?w=400" style="width: 100%; height: 140px; object-fit: cover;">
                <div style="padding: 10px;">
                    <div style="font-size: 18px; font-weight: bold; margin-bottom: 5px;">₹ 450</div>
                    <div style="font-size: 14px; color: #406367; white-space: nowrap; overflow: hidden; text-overflow: ellipsis;">Cotton Double Bedsheet</div>
                    <div style="font-size: 11px; color: #777; margin-top: 10px; display: flex; justify-content: space-between;">
                        <span>Sukhdev Nagar</span>
                    </div>
                </div>
                <i class="fa-regular fa-heart" style="position: absolute; top: 10px; right: 10px; background: white; padding: 6px; border-radius: 50%; color: #002f34; box-shadow: 0 2px 4px rgba(0,0,0,0.1);"></i>
            </div>

            <!-- आइटम 3: बाइक -->
            <div style="background-color: #fff; border: 1px solid #ccd5d6; border-radius: 4px; overflow: hidden; position: relative;">
                <img src="https://images.unsplash.com/photo-1558981806-ec527fa84c39?w=400" style="width: 100%; height: 140px; object-fit: cover;">
                <div style="padding: 10px;">
                    <div style="font-size: 18px; font-weight: bold; margin-bottom: 5px;">₹ 35,000</div>
                    <div style="font-size: 14px; color: #406367; white-space: nowrap; overflow: hidden; text-overflow: ellipsis;">Splendor Plus 2021</div>
                    <div style="font-size: 11px; color: #777; margin-top: 10px; display: flex; justify-content: space-between;">
                        <span>Sector 11, Panipat</span>
                    </div>
                </div>
                <i class="fa-regular fa-heart" style="position: absolute; top: 10px; right: 10px; background: white; padding: 6px; border-radius: 50%; color: #002f34; box-shadow: 0 2px 4px rgba(0,0,0,0.1);"></i>
            </div>

            <!-- आइटम 4: स्टडी टेबल -->
            <div style="background-color: #fff; border: 1px solid #ccd5d6; border-radius: 4px; overflow: hidden; position: relative;">
                <img src="https://images.unsplash.com/photo-1518455027359-f3f8164ba6bd?w=400" style="width: 100%; height: 140px; object-fit: cover;">
                <div style="padding: 10px;">
                    <div style="font-size: 18px; font-weight: bold; margin-bottom: 5px;">₹ 1,200</div>
                    <div style="font-size: 14px; color: #406367; white-space: nowrap; overflow: hidden; text-overflow: ellipsis;">Wooden Study Table</div>
                    <div style="font-size: 11px; color: #777; margin-top: 10px; display: flex; justify-content: space-between;">
                        <span>Gohana Road</span>
                    </div>
                </div>
                <i class="fa-regular fa-heart" style="position: absolute; top: 10px; right: 10px; background: white; padding: 6px; border-radius: 50%; color: #002f34; box-shadow: 0 2px 4px rgba(0,0,0,0.1);"></i>
            </div>

        </div>
    </main>

    <!-- फुटर -->
    <footer style="background-color: #002f34; color: #fff; text-align: center; padding: 15px; font-size: 12px;">
        <p>© 2026 Panipat Marketplace | Buy and Sell Old Items Online</p>
    </footer>

</body>
</html>
