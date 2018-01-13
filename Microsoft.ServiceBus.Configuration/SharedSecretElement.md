<Type Name="SharedSecretElement" FullName="Microsoft.ServiceBus.Configuration.SharedSecretElement">
  <TypeSignature Language="C#" Value="public class SharedSecretElement : System.Configuration.ConfigurationElement" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SharedSecretElement extends System.Configuration.ConfigurationElement" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Configuration.SharedSecretElement" />
  <TypeSignature Language="VB.NET" Value="Public Class SharedSecretElement&#xA;Inherits ConfigurationElement" />
  <TypeSignature Language="F#" Value="type SharedSecretElement = class&#xA;    inherit ConfigurationElement" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Configuration.ConfigurationElement</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>使用するように構成するサービスまたはクライアント エンドポイントの資格情報を指定する構成要素、<see cref="T:Microsoft.ServiceBus.SharedSecretTokenProvider" />資格情報の種類。</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CopyFrom">
      <MemberSignature Language="C#" Value="public void CopyFrom (Microsoft.ServiceBus.Configuration.SharedSecretElement source);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void CopyFrom(class Microsoft.ServiceBus.Configuration.SharedSecretElement source) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.SharedSecretElement.CopyFrom(Microsoft.ServiceBus.Configuration.SharedSecretElement)" />
      <MemberSignature Language="VB.NET" Value="Public Sub CopyFrom (source As SharedSecretElement)" />
      <MemberSignature Language="F#" Value="member this.CopyFrom : Microsoft.ServiceBus.Configuration.SharedSecretElement -&gt; unit" Usage="sharedSecretElement.CopyFrom source" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="source" Type="Microsoft.ServiceBus.Configuration.SharedSecretElement" />
      </Parameters>
      <Docs>
        <param name="source">コピーされる共有シークレット構成要素。</param>
        <summary>この構成要素に指定した共有シークレット構成要素の内容をコピーします。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IssuerName">
      <MemberSignature Language="C#" Value="public string IssuerName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string IssuerName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.SharedSecretElement.IssuerName" />
      <MemberSignature Language="VB.NET" Value="Public Property IssuerName As String" />
      <MemberSignature Language="F#" Value="member this.IssuerName : string with get, set" Usage="Microsoft.ServiceBus.Configuration.SharedSecretElement.IssuerName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("issuerName", IsRequired=true)</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Configuration.StringValidator(MaxLength=128, MinLength=0)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または発行者名を設定します。</summary>
        <value>発行者の名前。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IssuerSecret">
      <MemberSignature Language="C#" Value="public string IssuerSecret { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string IssuerSecret" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.SharedSecretElement.IssuerSecret" />
      <MemberSignature Language="VB.NET" Value="Public Property IssuerSecret As String" />
      <MemberSignature Language="F#" Value="member this.IssuerSecret : string with get, set" Usage="Microsoft.ServiceBus.Configuration.SharedSecretElement.IssuerSecret" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("issuerSecret", IsRequired=true)</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Configuration.StringValidator(MaxLength=128, MinLength=0)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または発行者のシークレット キーを設定します。</summary>
        <value>発行者のシークレット キー。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="protected override System.Configuration.ConfigurationPropertyCollection Properties { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Configuration.ConfigurationPropertyCollection Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.SharedSecretElement.Properties" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides ReadOnly Property Properties As ConfigurationPropertyCollection" />
      <MemberSignature Language="F#" Value="member this.Properties : System.Configuration.ConfigurationPropertyCollection" Usage="Microsoft.ServiceBus.Configuration.SharedSecretElement.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Configuration.ConfigurationPropertyCollection</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>発行者名と発行者のシークレット キーが含まれているこの構成要素のプロパティを取得します。</summary>
        <value>発行者名と発行者のシークレット キーを含む、この構成要素のプロパティです。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TokenScope">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.TokenScope TokenScope { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceBus.TokenScope TokenScope" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.SharedSecretElement.TokenScope" />
      <MemberSignature Language="VB.NET" Value="Public Property TokenScope As TokenScope" />
      <MemberSignature Language="F#" Value="member this.TokenScope : Microsoft.ServiceBus.TokenScope with get, set" Usage="Microsoft.ServiceBus.Configuration.SharedSecretElement.TokenScope" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("tokenScope", DefaultValue=Mono.Cecil.CustomAttributeArgument, IsRequired=false)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.TokenScope</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはトークンのスコープを設定します。</summary>
        <value>トークンのスコープです。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>