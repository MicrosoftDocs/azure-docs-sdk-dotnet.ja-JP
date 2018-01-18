<Type Name="TokenProviderElementCollection" FullName="Microsoft.Azure.NotificationHubs.Configuration.TokenProviderElementCollection">
  <TypeSignature Language="C#" Value="public sealed class TokenProviderElementCollection : System.Configuration.ConfigurationElementCollection" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit TokenProviderElementCollection extends System.Configuration.ConfigurationElementCollection" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.NotificationHubs.Configuration.TokenProviderElementCollection" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class TokenProviderElementCollection&#xA;Inherits ConfigurationElementCollection" />
  <TypeSignature Language="F#" Value="type TokenProviderElementCollection = class&#xA;    inherit ConfigurationElementCollection" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.16.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Configuration.ConfigurationElementCollection</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Configuration.ConfigurationCollection(typeof(Microsoft.Azure.NotificationHubs.Configuration.TokenProviderElement), CollectionType=System.Configuration.ConfigurationElementCollectionType.AddRemoveClearMap)</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary><span data-ttu-id="851b7-101">トークン プロバイダーの要素のコレクションを表します。</span><span class="sxs-lookup"><span data-stu-id="851b7-101">Represents a collection of elements for the token provider.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TokenProviderElementCollection ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.Configuration.TokenProviderElementCollection.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="851b7-102"><see cref="T:Microsoft.Azure.NotificationHubs.Configuration.TokenProviderElementCollection" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="851b7-102">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.Configuration.TokenProviderElementCollection" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateNewElement">
      <MemberSignature Language="C#" Value="protected override System.Configuration.ConfigurationElement CreateNewElement ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.Configuration.ConfigurationElement CreateNewElement() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.Configuration.TokenProviderElementCollection.CreateNewElement" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function CreateNewElement () As ConfigurationElement" />
      <MemberSignature Language="F#" Value="override this.CreateNewElement : unit -&gt; System.Configuration.ConfigurationElement" Usage="tokenProviderElementCollection.CreateNewElement " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Configuration.ConfigurationElement</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="851b7-103">派生クラスでオーバーライドされると、新しい <see cref="T:System.Configuration.ConfigurationElement" /> を作成します。</span><span class="sxs-lookup"><span data-stu-id="851b7-103">When overridden in a derived class, creates a new <see cref="T:System.Configuration.ConfigurationElement" />.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="851b7-104">新しい <see cref="T:System.Configuration.ConfigurationElement" />。</span><span class="sxs-lookup"><span data-stu-id="851b7-104">A new <see cref="T:System.Configuration.ConfigurationElement" />.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetElementKey">
      <MemberSignature Language="C#" Value="protected override object GetElementKey (System.Configuration.ConfigurationElement element);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance object GetElementKey(class System.Configuration.ConfigurationElement element) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.Configuration.TokenProviderElementCollection.GetElementKey(System.Configuration.ConfigurationElement)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function GetElementKey (element As ConfigurationElement) As Object" />
      <MemberSignature Language="F#" Value="override this.GetElementKey : System.Configuration.ConfigurationElement -&gt; obj" Usage="tokenProviderElementCollection.GetElementKey element" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="element" Type="System.Configuration.ConfigurationElement" />
      </Parameters>
      <Docs>
        <param name="element"><span data-ttu-id="851b7-105">キーを返す <see cref="T:System.Configuration.ConfigurationElement" />。</span><span class="sxs-lookup"><span data-stu-id="851b7-105">The <see cref="T:System.Configuration.ConfigurationElement" /> to return the key for.</span></span></param>
        <summary>
            <span data-ttu-id="851b7-106">派生クラスでオーバーライドされた場合は、指定した構成要素の要素のキーを取得します。</span><span class="sxs-lookup"><span data-stu-id="851b7-106">Gets the element key for a specified configuration element when overridden in a derived class.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="851b7-107"><see cref="T:System.Object" /> 、指定されたキーとして機能する<see cref="T:System.Configuration.ConfigurationElement" />です。</span><span class="sxs-lookup"><span data-stu-id="851b7-107">An <see cref="T:System.Object" /> that acts as the key for the specified <see cref="T:System.Configuration.ConfigurationElement" />.</span></span>
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Configuration.ConfigurationErrorsException" />
      </Docs>
    </Member>
    <Member MemberName="Item">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.NotificationHubs.Configuration.TokenProviderElement this[string name] { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.NotificationHubs.Configuration.TokenProviderElement Item(string)" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.Configuration.TokenProviderElementCollection.Item(System.String)" />
      <MemberSignature Language="VB.NET" Value="Default Public ReadOnly Property Item(name As String) As TokenProviderElement" />
      <MemberSignature Language="F#" Value="member this.Item(string) : Microsoft.Azure.NotificationHubs.Configuration.TokenProviderElement" Usage="Microsoft.Azure.NotificationHubs.Configuration.TokenProviderElementCollection.Item" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.Configuration.TokenProviderElement</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="851b7-108">項目の名前。</span><span class="sxs-lookup"><span data-stu-id="851b7-108">The name of the item.</span></span></param>
        <summary><span data-ttu-id="851b7-109">コレクション内の項目を取得します。</span><span class="sxs-lookup"><span data-stu-id="851b7-109">Gets an item in the collection.</span></span></summary>
        <value><span data-ttu-id="851b7-110">コレクション内の項目。</span><span class="sxs-lookup"><span data-stu-id="851b7-110">An item in the collection.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>