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
    <summary>トークン プロバイダーの要素のコレクションを表します。</summary>
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
        <summary><see cref="T:Microsoft.Azure.NotificationHubs.Configuration.TokenProviderElementCollection" /> クラスの新しいインスタンスを初期化します。</summary>
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
            派生クラスでオーバーライドされると、新しい <see cref="T:System.Configuration.ConfigurationElement" /> を作成します。
            </summary>
        <returns>
            新しい <see cref="T:System.Configuration.ConfigurationElement" />。
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
        <param name="element">キーを返す <see cref="T:System.Configuration.ConfigurationElement" />。</param>
        <summary>
            派生クラスでオーバーライドされた場合は、指定した構成要素の要素のキーを取得します。
            </summary>
        <returns>
            <see cref="T:System.Object" /> 、指定されたキーとして機能する<see cref="T:System.Configuration.ConfigurationElement" />です。
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
        <param name="name">項目の名前。</param>
        <summary>コレクション内の項目を取得します。</summary>
        <value>コレクション内の項目。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>