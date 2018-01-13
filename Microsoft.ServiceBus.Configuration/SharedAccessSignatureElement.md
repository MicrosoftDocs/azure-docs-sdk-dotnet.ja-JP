<Type Name="SharedAccessSignatureElement" FullName="Microsoft.ServiceBus.Configuration.SharedAccessSignatureElement">
  <TypeSignature Language="C#" Value="public class SharedAccessSignatureElement : System.Configuration.ConfigurationElement" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SharedAccessSignatureElement extends System.Configuration.ConfigurationElement" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Configuration.SharedAccessSignatureElement" />
  <TypeSignature Language="VB.NET" Value="Public Class SharedAccessSignatureElement&#xA;Inherits ConfigurationElement" />
  <TypeSignature Language="F#" Value="type SharedAccessSignatureElement = class&#xA;    inherit ConfigurationElement" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Configuration.ConfigurationElement</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>共有アクセス署名の要素を表します。</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CopyFrom">
      <MemberSignature Language="C#" Value="public void CopyFrom (Microsoft.ServiceBus.Configuration.SharedAccessSignatureElement source);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void CopyFrom(class Microsoft.ServiceBus.Configuration.SharedAccessSignatureElement source) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.SharedAccessSignatureElement.CopyFrom(Microsoft.ServiceBus.Configuration.SharedAccessSignatureElement)" />
      <MemberSignature Language="VB.NET" Value="Public Sub CopyFrom (source As SharedAccessSignatureElement)" />
      <MemberSignature Language="F#" Value="member this.CopyFrom : Microsoft.ServiceBus.Configuration.SharedAccessSignatureElement -&gt; unit" Usage="sharedAccessSignatureElement.CopyFrom source" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="source" Type="Microsoft.ServiceBus.Configuration.SharedAccessSignatureElement" />
      </Parameters>
      <Docs>
        <param name="source">内容をコピーするソース。</param>
        <summary>この構成要素から指定した要素をコピーします。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Key">
      <MemberSignature Language="C#" Value="public string Key { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Key" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.SharedAccessSignatureElement.Key" />
      <MemberSignature Language="VB.NET" Value="Public Property Key As String" />
      <MemberSignature Language="F#" Value="member this.Key : string with get, set" Usage="Microsoft.ServiceBus.Configuration.SharedAccessSignatureElement.Key" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("key", IsRequired=true)</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Configuration.StringValidator(MaxLength=256, MinLength=0)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または共有アクセス キーを設定します。</summary>
        <value>共有アクセス キー。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeyName">
      <MemberSignature Language="C#" Value="public string KeyName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string KeyName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.SharedAccessSignatureElement.KeyName" />
      <MemberSignature Language="VB.NET" Value="Public Property KeyName As String" />
      <MemberSignature Language="F#" Value="member this.KeyName : string with get, set" Usage="Microsoft.ServiceBus.Configuration.SharedAccessSignatureElement.KeyName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("keyName", IsRequired=true)</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Configuration.StringValidator(MaxLength=256, MinLength=0)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または共有アクセス キーの名前を設定します。</summary>
        <value>共有アクセス キーの名前。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="protected override System.Configuration.ConfigurationPropertyCollection Properties { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Configuration.ConfigurationPropertyCollection Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.SharedAccessSignatureElement.Properties" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides ReadOnly Property Properties As ConfigurationPropertyCollection" />
      <MemberSignature Language="F#" Value="member this.Properties : System.Configuration.ConfigurationPropertyCollection" Usage="Microsoft.ServiceBus.Configuration.SharedAccessSignatureElement.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Configuration.ConfigurationPropertyCollection</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>構成プロパティのコレクションを取得します。</summary>
        <value>構成プロパティのコレクション。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TokenScope">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.TokenScope TokenScope { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceBus.TokenScope TokenScope" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.SharedAccessSignatureElement.TokenScope" />
      <MemberSignature Language="VB.NET" Value="Public Property TokenScope As TokenScope" />
      <MemberSignature Language="F#" Value="member this.TokenScope : Microsoft.ServiceBus.TokenScope with get, set" Usage="Microsoft.ServiceBus.Configuration.SharedAccessSignatureElement.TokenScope" />
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
        <summary>取得または要素に関連付けられているトークンのスコープを設定します。</summary>
        <value>要素に関連付けられているトークンのスコープです。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>