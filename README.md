import React from "react";
import { Button } from "@/components/ui/button";
import { Card, CardContent } from "@/components/ui/card";

const PizzaParlor = () => {
  return (
    <div className="min-h-screen bg-white text-gray-900 p-4">
      <header className="text-center py-8">
        <h1 className="text-4xl font-bold">Mama Z's Pizza Parlor</h1>
        <p className="text-lg mt-2">The best slice in town, made with love.</p>
      </header>

      <section className="grid gap-4 md:grid-cols-3 py-8">
        <Card>
          <CardContent className="p-4 text-center">
            <h2 className="text-2xl font-semibold mb-2">Classic Pepperoni</h2>
            <p>Loaded with premium pepperoni and mozzarella on a crispy crust.</p>
            <Button className="mt-4">Order Now</Button>
          </CardContent>
        </Card>

        <Card>
          <CardContent className="p-4 text-center">
            <h2 className="text-2xl font-semibold mb-2">Margherita</h2>
            <p>Fresh basil, ripe tomatoes, and creamy mozzarella.</p>
            <Button className="mt-4">Order Now</Button>
          </CardContent>
        </Card>

        <Card>
          <CardContent className="p-4 text-center">
            <h2 className="text-2xl font-semibold mb-2">Meat Lovers</h2>
            <p>Sausage, ham, pepperoni, and bacon. A carnivore's dream.</p>
            <Button className="mt-4">Order Now</Button>
          </CardContent>
        </Card>
      </section>

      <section className="py-8 text-center">
        <h2 className="text-3xl font-bold mb-4">Visit Us</h2>
        <p>123 Main Street, Pizza Town, USA</p>
        <p>Open Daily: 11 AM - 10 PM</p>
      </section>

      <footer className="text-center py-4 text-sm text-gray-600">
        &copy; 2025 Mama Z's Pizza Parlor. All rights reserved.
      </footer>
    </div>
  );
};

export default PizzaParlor;
