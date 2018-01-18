<Type Name="JsonSerializable" FullName="Microsoft.Azure.Documents.JsonSerializable">
  <TypeSignature Language="C#" Value="public abstract class JsonSerializable" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit JsonSerializable extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.JsonSerializable" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class JsonSerializable" />
  <TypeSignature Language="F#" Value="type JsonSerializable = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
    <AssemblyVersion>1.6.0.0</AssemblyVersion>
    <AssemblyVersion>1.7.0.0</AssemblyVersion>
    <AssemblyVersion>1.7.1.0</AssemblyVersion>
  </AssemblyInfo>
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
    <AssemblyVersion>1.18.0.0</AssemblyVersion>
    <AssemblyVersion>1.19.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="a88d2-101">Azure Cosmos DB データベース オブジェクトの基本クラスを表し、シリアル化すると、JSON から逆シリアル化メソッドを提供します。</span><span class="sxs-lookup"><span data-stu-id="a88d2-101">Represents the base class for Azure Cosmos DB database objects and provides methods for serializing and deserializing from JSON.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="LoadFrom">
      <MemberSignature Language="C#" Value="public virtual void LoadFrom (Newtonsoft.Json.JsonReader reader);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void LoadFrom(class Newtonsoft.Json.JsonReader reader) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.JsonSerializable.LoadFrom(Newtonsoft.Json.JsonReader)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub LoadFrom (reader As JsonReader)" />
      <MemberSignature Language="F#" Value="abstract member LoadFrom : Newtonsoft.Json.JsonReader -&gt; unit&#xA;override this.LoadFrom : Newtonsoft.Json.JsonReader -&gt; unit" Usage="jsonSerializable.LoadFrom reader" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="reader" Type="Newtonsoft.Json.JsonReader" />
      </Parameters>
      <Docs>
        <param name="reader"><span data-ttu-id="a88d2-102">この JSON リーダーからオブジェクトを読み込みます。</span><span class="sxs-lookup"><span data-stu-id="a88d2-102">Loads the object from this JSON reader.</span></span></param>
        <summary>
            <span data-ttu-id="a88d2-103">Azure Cosmos DB サービスの指定した JSON リーダーからオブジェクトを読み込みます。</span><span class="sxs-lookup"><span data-stu-id="a88d2-103">Loads the object from the specified JSON reader in the Azure Cosmos DB service.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LoadFrom">
      <MemberSignature Language="C#" Value="public virtual void LoadFrom (Newtonsoft.Json.JsonReader reader, Newtonsoft.Json.JsonSerializerSettings serializerSettings);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void LoadFrom(class Newtonsoft.Json.JsonReader reader, class Newtonsoft.Json.JsonSerializerSettings serializerSettings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.JsonSerializable.LoadFrom(Newtonsoft.Json.JsonReader,Newtonsoft.Json.JsonSerializerSettings)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub LoadFrom (reader As JsonReader, serializerSettings As JsonSerializerSettings)" />
      <MemberSignature Language="F#" Value="abstract member LoadFrom : Newtonsoft.Json.JsonReader * Newtonsoft.Json.JsonSerializerSettings -&gt; unit&#xA;override this.LoadFrom : Newtonsoft.Json.JsonReader * Newtonsoft.Json.JsonSerializerSettings -&gt; unit" Usage="jsonSerializable.LoadFrom (reader, serializerSettings)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="reader" Type="Newtonsoft.Json.JsonReader" />
        <Parameter Name="serializerSettings" Type="Newtonsoft.Json.JsonSerializerSettings" />
      </Parameters>
      <Docs>
        <param name="reader"><span data-ttu-id="a88d2-104">この JSON リーダーからオブジェクトを読み込みます。</span><span class="sxs-lookup"><span data-stu-id="a88d2-104">Loads the object from this JSON reader.</span></span></param>
        <param name="serializerSettings"><span data-ttu-id="a88d2-105">使用する JsonSerializerSettings。</span><span class="sxs-lookup"><span data-stu-id="a88d2-105">The JsonSerializerSettings to be used.</span></span></param>
        <summary>
            <span data-ttu-id="a88d2-106">Azure Cosmos DB サービスの指定した JSON リーダーからオブジェクトを読み込みます。</span><span class="sxs-lookup"><span data-stu-id="a88d2-106">Loads the object from the specified JSON reader in the Azure Cosmos DB service.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LoadFrom&lt;T&gt;">
      <MemberSignature Language="C#" Value="public static T LoadFrom&lt;T&gt; (System.IO.Stream stream) where T : Microsoft.Azure.Documents.JsonSerializablenew();" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig !!T LoadFrom&lt;.ctor (class Microsoft.Azure.Documents.JsonSerializable) T&gt;(class System.IO.Stream stream) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.JsonSerializable.LoadFrom``1(System.IO.Stream)" />
      <MemberSignature Language="F#" Value="static member LoadFrom : System.IO.Stream -&gt; 'T (requires 'T :&gt; Microsoft.Azure.Documents.JsonSerializable and 'T : (new : unit -&gt; 'T))" Usage="Microsoft.Azure.Documents.JsonSerializable.LoadFrom stream" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>T</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <ParameterAttribute>DefaultConstructorConstraint</ParameterAttribute>
            <BaseTypeName>Microsoft.Azure.Documents.JsonSerializable</BaseTypeName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="stream" Type="System.IO.Stream" />
      </Parameters>
      <Docs>
        <typeparam name="T"><span data-ttu-id="a88d2-107">返されるオブジェクトの型。</span><span class="sxs-lookup"><span data-stu-id="a88d2-107">The type of the returning object.</span></span></typeparam>
        <param name="stream"><span data-ttu-id="a88d2-108">読み込むストリーム。</span><span class="sxs-lookup"><span data-stu-id="a88d2-108">The stream to load from.</span></span></param>
        <summary>
            <span data-ttu-id="a88d2-109">Cosmos DB の Azure サービスで指定したストリームからオブジェクトを読み込みます。</span><span class="sxs-lookup"><span data-stu-id="a88d2-109">Loads the object from the specified stream in the Azure Cosmos DB service.</span></span>
            </summary>
        <returns><span data-ttu-id="a88d2-110">オブジェクトは、指定したストリームから読み込まれます。</span><span class="sxs-lookup"><span data-stu-id="a88d2-110">The object loaded from the specified stream.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LoadFromWithConstructor&lt;T&gt;">
      <MemberSignature Language="C#" Value="public static T LoadFromWithConstructor&lt;T&gt; (System.IO.Stream stream, Func&lt;T&gt; constructorFunction);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig !!T LoadFromWithConstructor&lt;T&gt;(class System.IO.Stream stream, class System.Func`1&lt;!!T&gt; constructorFunction) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.JsonSerializable.LoadFromWithConstructor``1(System.IO.Stream,System.Func{``0})" />
      <MemberSignature Language="F#" Value="static member LoadFromWithConstructor : System.IO.Stream * Func&lt;'T&gt; -&gt; 'T" Usage="Microsoft.Azure.Documents.JsonSerializable.LoadFromWithConstructor (stream, constructorFunction)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>T</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="stream" Type="System.IO.Stream" />
        <Parameter Name="constructorFunction" Type="System.Func&lt;T&gt;" />
      </Parameters>
      <Docs>
        <typeparam name="T"><span data-ttu-id="a88d2-111">オブジェクトの型。</span><span class="sxs-lookup"><span data-stu-id="a88d2-111">The type of the object.</span></span></typeparam>
        <param name="stream"><span data-ttu-id="a88d2-112">読み込むストリーム。</span><span class="sxs-lookup"><span data-stu-id="a88d2-112">The stream to load from.</span></span></param>
        <param name="constructorFunction"><span data-ttu-id="a88d2-113">返されるオブジェクトに使用されるコンス トラクターです。</span><span class="sxs-lookup"><span data-stu-id="a88d2-113">The constructor used for the returning object.</span></span></param>
        <summary>
            <span data-ttu-id="a88d2-114">Azure Cosmos DB サービスの特定のコンス トラクターを使用して、指定されたストリームを逆シリアル化します。</span><span class="sxs-lookup"><span data-stu-id="a88d2-114">Deserializes the specified stream using the given constructor in the Azure Cosmos DB service.</span></span>
            </summary>
        <returns><span data-ttu-id="a88d2-115">オブジェクトは、指定したストリームから読み込まれます。</span><span class="sxs-lookup"><span data-stu-id="a88d2-115">The object loaded from the specified stream.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LoadFromWithConstructor&lt;T&gt;">
      <MemberSignature Language="C#" Value="public static T LoadFromWithConstructor&lt;T&gt; (System.IO.Stream stream, Func&lt;T&gt; constructorFunction, Newtonsoft.Json.JsonSerializerSettings settings);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig !!T LoadFromWithConstructor&lt;T&gt;(class System.IO.Stream stream, class System.Func`1&lt;!!T&gt; constructorFunction, class Newtonsoft.Json.JsonSerializerSettings settings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.JsonSerializable.LoadFromWithConstructor``1(System.IO.Stream,System.Func{``0},Newtonsoft.Json.JsonSerializerSettings)" />
      <MemberSignature Language="F#" Value="static member LoadFromWithConstructor : System.IO.Stream * Func&lt;'T&gt; * Newtonsoft.Json.JsonSerializerSettings -&gt; 'T" Usage="Microsoft.Azure.Documents.JsonSerializable.LoadFromWithConstructor (stream, constructorFunction, settings)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>T</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="stream" Type="System.IO.Stream" />
        <Parameter Name="constructorFunction" Type="System.Func&lt;T&gt;" />
        <Parameter Name="settings" Type="Newtonsoft.Json.JsonSerializerSettings" />
      </Parameters>
      <Docs>
        <typeparam name="T"><span data-ttu-id="a88d2-116">オブジェクトの型。</span><span class="sxs-lookup"><span data-stu-id="a88d2-116">The type of the object.</span></span></typeparam>
        <param name="stream"><span data-ttu-id="a88d2-117">読み込むストリーム。</span><span class="sxs-lookup"><span data-stu-id="a88d2-117">The stream to load from.</span></span></param>
        <param name="constructorFunction"><span data-ttu-id="a88d2-118">返されるオブジェクトに使用されるコンス トラクターです。</span><span class="sxs-lookup"><span data-stu-id="a88d2-118">The constructor used for the returning object.</span></span></param>
        <param name="settings"><span data-ttu-id="a88d2-119">使用する JsonSerializerSettings。</span><span class="sxs-lookup"><span data-stu-id="a88d2-119">The JsonSerializerSettings to be used.</span></span></param>
        <summary>
            <span data-ttu-id="a88d2-120">Azure Cosmos DB サービスの特定のコンス トラクターを使用して、指定されたストリームを逆シリアル化します。</span><span class="sxs-lookup"><span data-stu-id="a88d2-120">Deserializes the specified stream using the given constructor in the Azure Cosmos DB service.</span></span>
            </summary>
        <returns><span data-ttu-id="a88d2-121">オブジェクトは、指定したストリームから読み込まれます。</span><span class="sxs-lookup"><span data-stu-id="a88d2-121">The object loaded from the specified stream.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SaveTo">
      <MemberSignature Language="C#" Value="public void SaveTo (System.IO.Stream stream, Microsoft.Azure.Documents.SerializationFormattingPolicy formattingPolicy = Microsoft.Azure.Documents.SerializationFormattingPolicy.None);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void SaveTo(class System.IO.Stream stream, valuetype Microsoft.Azure.Documents.SerializationFormattingPolicy formattingPolicy) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.JsonSerializable.SaveTo(System.IO.Stream,Microsoft.Azure.Documents.SerializationFormattingPolicy)" />
      <MemberSignature Language="F#" Value="member this.SaveTo : System.IO.Stream * Microsoft.Azure.Documents.SerializationFormattingPolicy -&gt; unit" Usage="jsonSerializable.SaveTo (stream, formattingPolicy)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="stream" Type="System.IO.Stream" />
        <Parameter Name="formattingPolicy" Type="Microsoft.Azure.Documents.SerializationFormattingPolicy" />
      </Parameters>
      <Docs>
        <param name="stream"><span data-ttu-id="a88d2-122">この出力ストリームにオブジェクトを保存します。</span><span class="sxs-lookup"><span data-stu-id="a88d2-122">Saves the object to this output stream.</span></span></param>
        <param name="formattingPolicy"><span data-ttu-id="a88d2-123">シリアル化が省略可能であることをオブジェクトを保存するときに、ポリシーを書式設定を使用します。</span><span class="sxs-lookup"><span data-stu-id="a88d2-123">Uses an optional serialization formatting policy when saving the object.</span></span> <span data-ttu-id="a88d2-124">既定のポリシーは、[なし] に設定されます。</span><span class="sxs-lookup"><span data-stu-id="a88d2-124">The default policy is set to None.</span></span></param>
        <summary> 
            <span data-ttu-id="a88d2-125">Cosmos DB の Azure サービスで指定したストリームにオブジェクトを保存します。</span><span class="sxs-lookup"><span data-stu-id="a88d2-125">Saves the object to the specified stream in the Azure Cosmos DB service.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SaveTo">
      <MemberSignature Language="C#" Value="public void SaveTo (System.IO.Stream stream, Microsoft.Azure.Documents.SerializationFormattingPolicy formattingPolicy, Newtonsoft.Json.JsonSerializerSettings settings);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void SaveTo(class System.IO.Stream stream, valuetype Microsoft.Azure.Documents.SerializationFormattingPolicy formattingPolicy, class Newtonsoft.Json.JsonSerializerSettings settings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.JsonSerializable.SaveTo(System.IO.Stream,Microsoft.Azure.Documents.SerializationFormattingPolicy,Newtonsoft.Json.JsonSerializerSettings)" />
      <MemberSignature Language="F#" Value="member this.SaveTo : System.IO.Stream * Microsoft.Azure.Documents.SerializationFormattingPolicy * Newtonsoft.Json.JsonSerializerSettings -&gt; unit" Usage="jsonSerializable.SaveTo (stream, formattingPolicy, settings)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="stream" Type="System.IO.Stream" />
        <Parameter Name="formattingPolicy" Type="Microsoft.Azure.Documents.SerializationFormattingPolicy" />
        <Parameter Name="settings" Type="Newtonsoft.Json.JsonSerializerSettings" />
      </Parameters>
      <Docs>
        <param name="stream"><span data-ttu-id="a88d2-126">この出力ストリームにオブジェクトを保存します。</span><span class="sxs-lookup"><span data-stu-id="a88d2-126">Saves the object to this output stream.</span></span></param>
        <param name="formattingPolicy"><span data-ttu-id="a88d2-127">オブジェクトを保存するときに、ポリシーを書式設定、カスタムのシリアル化を使用します。</span><span class="sxs-lookup"><span data-stu-id="a88d2-127">Uses a custom serialization formatting policy when saving the object.</span></span></param>
        <param name="settings"><span data-ttu-id="a88d2-128">使用するシリアライザーの設定。</span><span class="sxs-lookup"><span data-stu-id="a88d2-128">The serializer settings to use.</span></span></param>
        <summary> 
            <span data-ttu-id="a88d2-129">Cosmos DB の Azure サービスで指定したストリームにオブジェクトを保存します。</span><span class="sxs-lookup"><span data-stu-id="a88d2-129">Saves the object to the specified stream in the Azure Cosmos DB service.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.JsonSerializable.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="jsonSerializable.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="a88d2-130">Azure Cosmos DB サービスのオブジェクトの文字列表現を返します。</span><span class="sxs-lookup"><span data-stu-id="a88d2-130">Returns the string representation of the object in the Azure Cosmos DB service.</span></span>
            </summary>
        <returns><span data-ttu-id="a88d2-131">オブジェクトの文字列表現。</span><span class="sxs-lookup"><span data-stu-id="a88d2-131">The string representation of the object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>