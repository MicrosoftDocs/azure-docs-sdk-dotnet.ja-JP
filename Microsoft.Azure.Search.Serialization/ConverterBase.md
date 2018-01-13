<Type Name="ConverterBase" FullName="Microsoft.Azure.Search.Serialization.ConverterBase">
  <TypeSignature Language="C#" Value="public abstract class ConverterBase : Newtonsoft.Json.JsonConverter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit ConverterBase extends Newtonsoft.Json.JsonConverter" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Serialization.ConverterBase" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class ConverterBase&#xA;Inherits JsonConverter" />
  <TypeSignature Language="F#" Value="type ConverterBase = class&#xA;    inherit JsonConverter" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Search</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Newtonsoft.Json.JsonConverter</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="c5301-101">カスタム JsonConverters の基本クラス。</span><span class="sxs-lookup"><span data-stu-id="c5301-101">Base class for custom JsonConverters.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected ConverterBase ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Serialization.ConverterBase.#ctor" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Advance">
      <MemberSignature Language="C#" Value="protected void Advance (Newtonsoft.Json.JsonReader reader);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig instance void Advance(class Newtonsoft.Json.JsonReader reader) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Serialization.ConverterBase.Advance(Newtonsoft.Json.JsonReader)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub Advance (reader As JsonReader)" />
      <MemberSignature Language="F#" Value="member this.Advance : Newtonsoft.Json.JsonReader -&gt; unit" Usage="converterBase.Advance reader" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="reader" Type="Newtonsoft.Json.JsonReader" />
      </Parameters>
      <Docs>
        <param name="reader"><span data-ttu-id="c5301-102">進める JSON リーダーです。</span><span class="sxs-lookup"><span data-stu-id="c5301-102">The JSON reader to advance.</span></span></param>
        <summary>
            <span data-ttu-id="c5301-103">指定した JSON リーダーを進めます。 またはそのできない高度な場合は、JsonSerializationException をスローします。</span><span class="sxs-lookup"><span data-stu-id="c5301-103">Advances the given JSON reader, or throws a JsonSerializationException if it cannot be advanced.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Expect">
      <MemberSignature Language="C#" Value="protected void Expect (Newtonsoft.Json.JsonReader reader, Newtonsoft.Json.JsonToken expectedToken, object expectedValue = null);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig instance void Expect(class Newtonsoft.Json.JsonReader reader, valuetype Newtonsoft.Json.JsonToken expectedToken, object expectedValue) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Serialization.ConverterBase.Expect(Newtonsoft.Json.JsonReader,Newtonsoft.Json.JsonToken,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub Expect (reader As JsonReader, expectedToken As JsonToken, Optional expectedValue As Object = null)" />
      <MemberSignature Language="F#" Value="member this.Expect : Newtonsoft.Json.JsonReader * Newtonsoft.Json.JsonToken * obj -&gt; unit" Usage="converterBase.Expect (reader, expectedToken, expectedValue)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="reader" Type="Newtonsoft.Json.JsonReader" />
        <Parameter Name="expectedToken" Type="Newtonsoft.Json.JsonToken" />
        <Parameter Name="expectedValue" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="reader"><span data-ttu-id="c5301-104">JSON リーダーです。</span><span class="sxs-lookup"><span data-stu-id="c5301-104">The JSON reader.</span></span></param>
        <param name="expectedToken"><span data-ttu-id="c5301-105">リーダーが配置される予定 JSON トークンです。</span><span class="sxs-lookup"><span data-stu-id="c5301-105">The JSON token on which the reader is expected to be positioned.</span></span></param>
        <param name="expectedValue"><span data-ttu-id="c5301-106">省略可能です。現在の JSON トークンの予期される値。</span><span class="sxs-lookup"><span data-stu-id="c5301-106">Optional; The expected value of the current JSON token.</span></span></param>
        <summary>
            <span data-ttu-id="c5301-107">予期された型、トークンに指定した JSON リーダーが配置されていることをアサートします。</span><span class="sxs-lookup"><span data-stu-id="c5301-107">Asserts that the given JSON reader is positioned on a token with the expected type.</span></span> <span data-ttu-id="c5301-108">必要に応じて、トークンの値が、指定された予想値と一致することをアサートします。</span><span class="sxs-lookup"><span data-stu-id="c5301-108">Optionally asserts that the value of the token matches a given expected value.</span></span> <span data-ttu-id="c5301-109">アサーションの失敗した場合、このメソッドは、JsonSerializationException をスローします。</span><span class="sxs-lookup"><span data-stu-id="c5301-109">If any of the assertions fail, this method throws a JsonSerializationException.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Expect&lt;TValue&gt;">
      <MemberSignature Language="C#" Value="protected TValue Expect&lt;TValue&gt; (Newtonsoft.Json.JsonReader reader, Newtonsoft.Json.JsonToken expectedToken, object expectedValue = null);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig instance !!TValue Expect&lt;TValue&gt;(class Newtonsoft.Json.JsonReader reader, valuetype Newtonsoft.Json.JsonToken expectedToken, object expectedValue) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Serialization.ConverterBase.Expect``1(Newtonsoft.Json.JsonReader,Newtonsoft.Json.JsonToken,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected Function Expect(Of TValue) (reader As JsonReader, expectedToken As JsonToken, Optional expectedValue As Object = null) As TValue" />
      <MemberSignature Language="F#" Value="member this.Expect : Newtonsoft.Json.JsonReader * Newtonsoft.Json.JsonToken * obj -&gt; 'Value" Usage="converterBase.Expect (reader, expectedToken, expectedValue)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>TValue</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TValue" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="reader" Type="Newtonsoft.Json.JsonReader" />
        <Parameter Name="expectedToken" Type="Newtonsoft.Json.JsonToken" />
        <Parameter Name="expectedValue" Type="System.Object" />
      </Parameters>
      <Docs>
        <typeparam name="TValue"><span data-ttu-id="c5301-110">現在の JSON トークンの値の型。</span><span class="sxs-lookup"><span data-stu-id="c5301-110">The expected type of the value of the current JSON token.</span></span></typeparam>
        <param name="reader"><span data-ttu-id="c5301-111">JSON リーダーです。</span><span class="sxs-lookup"><span data-stu-id="c5301-111">The JSON reader.</span></span></param>
        <param name="expectedToken"><span data-ttu-id="c5301-112">リーダーが配置される予定 JSON トークンです。</span><span class="sxs-lookup"><span data-stu-id="c5301-112">The JSON token on which the reader is expected to be positioned.</span></span></param>
        <param name="expectedValue"><span data-ttu-id="c5301-113">省略可能です。現在の JSON トークンの予期される値。</span><span class="sxs-lookup"><span data-stu-id="c5301-113">Optional; The expected value of the current JSON token.</span></span></param>
        <summary>
            <span data-ttu-id="c5301-114">存在する場合は、指定した JSON リーダーが配置されているトークンに予期された型と、トークンの値を取得ことをアサートします。</span><span class="sxs-lookup"><span data-stu-id="c5301-114">Asserts that the given JSON reader is positioned on a token with the expected type and retrieves the value of the token, if any.</span></span> <span data-ttu-id="c5301-115">必要に応じて、トークンの値が、指定された予想値と一致することをアサートします。</span><span class="sxs-lookup"><span data-stu-id="c5301-115">Optionally asserts that the value of the token matches a given expected value.</span></span> <span data-ttu-id="c5301-116">アサーションの失敗した場合、このメソッドは、JsonSerializationException をスローします。</span><span class="sxs-lookup"><span data-stu-id="c5301-116">If any of the assertions fail, this method throws a JsonSerializationException.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="c5301-117">現在の JSON トークン、または default(TValue) 現在のトークンに値が存在しない場合の値。</span><span class="sxs-lookup"><span data-stu-id="c5301-117">The value of the current JSON token, or default(TValue) if the current token has no value.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExpectAndAdvance">
      <MemberSignature Language="C#" Value="protected void ExpectAndAdvance (Newtonsoft.Json.JsonReader reader, Newtonsoft.Json.JsonToken expectedToken, object expectedValue = null);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig instance void ExpectAndAdvance(class Newtonsoft.Json.JsonReader reader, valuetype Newtonsoft.Json.JsonToken expectedToken, object expectedValue) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Serialization.ConverterBase.ExpectAndAdvance(Newtonsoft.Json.JsonReader,Newtonsoft.Json.JsonToken,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub ExpectAndAdvance (reader As JsonReader, expectedToken As JsonToken, Optional expectedValue As Object = null)" />
      <MemberSignature Language="F#" Value="member this.ExpectAndAdvance : Newtonsoft.Json.JsonReader * Newtonsoft.Json.JsonToken * obj -&gt; unit" Usage="converterBase.ExpectAndAdvance (reader, expectedToken, expectedValue)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="reader" Type="Newtonsoft.Json.JsonReader" />
        <Parameter Name="expectedToken" Type="Newtonsoft.Json.JsonToken" />
        <Parameter Name="expectedValue" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="reader"><span data-ttu-id="c5301-118">JSON リーダーです。</span><span class="sxs-lookup"><span data-stu-id="c5301-118">The JSON reader.</span></span></param>
        <param name="expectedToken"><span data-ttu-id="c5301-119">リーダーが配置される予定 JSON トークンです。</span><span class="sxs-lookup"><span data-stu-id="c5301-119">The JSON token on which the reader is expected to be positioned.</span></span></param>
        <param name="expectedValue"><span data-ttu-id="c5301-120">省略可能です。現在の JSON トークンの予期される値。</span><span class="sxs-lookup"><span data-stu-id="c5301-120">Optional; The expected value of the current JSON token.</span></span></param>
        <summary>
            <span data-ttu-id="c5301-121">予期された型、トークンに指定した JSON リーダーが配置されていることをアサートします。</span><span class="sxs-lookup"><span data-stu-id="c5301-121">Asserts that the given JSON reader is positioned on a token with the expected type.</span></span> <span data-ttu-id="c5301-122">必要に応じて、トークンの値が、指定された予想値と一致することをアサートします。</span><span class="sxs-lookup"><span data-stu-id="c5301-122">Optionally asserts that the value of the token matches a given expected value.</span></span> <span data-ttu-id="c5301-123">アサーションの失敗した場合、このメソッドは、JsonSerializationException をスローします。</span><span class="sxs-lookup"><span data-stu-id="c5301-123">If any of the assertions fail, this method throws a JsonSerializationException.</span></span> <span data-ttu-id="c5301-124">それ以外の場合、このメソッドは、JSON リーダーの次の位置を進めしようとします。</span><span class="sxs-lookup"><span data-stu-id="c5301-124">Otherwise, this method attempts to advance the JSON reader to the next position.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExpectAndAdvance&lt;TValue&gt;">
      <MemberSignature Language="C#" Value="protected TValue ExpectAndAdvance&lt;TValue&gt; (Newtonsoft.Json.JsonReader reader, Newtonsoft.Json.JsonToken expectedToken, object expectedValue = null);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig instance !!TValue ExpectAndAdvance&lt;TValue&gt;(class Newtonsoft.Json.JsonReader reader, valuetype Newtonsoft.Json.JsonToken expectedToken, object expectedValue) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Serialization.ConverterBase.ExpectAndAdvance``1(Newtonsoft.Json.JsonReader,Newtonsoft.Json.JsonToken,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected Function ExpectAndAdvance(Of TValue) (reader As JsonReader, expectedToken As JsonToken, Optional expectedValue As Object = null) As TValue" />
      <MemberSignature Language="F#" Value="member this.ExpectAndAdvance : Newtonsoft.Json.JsonReader * Newtonsoft.Json.JsonToken * obj -&gt; 'Value" Usage="converterBase.ExpectAndAdvance (reader, expectedToken, expectedValue)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>TValue</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TValue" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="reader" Type="Newtonsoft.Json.JsonReader" />
        <Parameter Name="expectedToken" Type="Newtonsoft.Json.JsonToken" />
        <Parameter Name="expectedValue" Type="System.Object" />
      </Parameters>
      <Docs>
        <typeparam name="TValue"><span data-ttu-id="c5301-125">現在の JSON トークンの値の型。</span><span class="sxs-lookup"><span data-stu-id="c5301-125">The expected type of the value of the current JSON token.</span></span></typeparam>
        <param name="reader"><span data-ttu-id="c5301-126">JSON リーダーです。</span><span class="sxs-lookup"><span data-stu-id="c5301-126">The JSON reader.</span></span></param>
        <param name="expectedToken"><span data-ttu-id="c5301-127">リーダーが配置される予定 JSON トークンです。</span><span class="sxs-lookup"><span data-stu-id="c5301-127">The JSON token on which the reader is expected to be positioned.</span></span></param>
        <param name="expectedValue"><span data-ttu-id="c5301-128">省略可能です。現在の JSON トークンの予期される値。</span><span class="sxs-lookup"><span data-stu-id="c5301-128">Optional; The expected value of the current JSON token.</span></span></param>
        <summary>
            <span data-ttu-id="c5301-129">存在する場合は、指定した JSON リーダーが配置されているトークンに予期された型と、トークンの値を取得ことをアサートします。</span><span class="sxs-lookup"><span data-stu-id="c5301-129">Asserts that the given JSON reader is positioned on a token with the expected type and retrieves the value of the token, if any.</span></span> <span data-ttu-id="c5301-130">必要に応じて、トークンの値が、指定された予想値と一致することをアサートします。</span><span class="sxs-lookup"><span data-stu-id="c5301-130">Optionally asserts that the value of the token matches a given expected value.</span></span> <span data-ttu-id="c5301-131">アサーションの失敗した場合、このメソッドは、JsonSerializationException をスローします。</span><span class="sxs-lookup"><span data-stu-id="c5301-131">If any of the assertions fail, this method throws a JsonSerializationException.</span></span> <span data-ttu-id="c5301-132">それ以外の場合、このメソッドは、JSON リーダーの次の位置を進めしようとします。</span><span class="sxs-lookup"><span data-stu-id="c5301-132">Otherwise, this method attempts to advance the JSON reader to the next position.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="c5301-133">トークンに値が存在しない場合は、reader、または default(TValue) を進める前に、JSON トークンの値。</span><span class="sxs-lookup"><span data-stu-id="c5301-133">The value of the JSON token before advancing the reader, or default(TValue) if the token has no value.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>