<Type Name="SharedAccessSignatureElement" FullName="Microsoft.Azure.NotificationHubs.Configuration.SharedAccessSignatureElement">
  <TypeSignature Language="C#" Value="public class SharedAccessSignatureElement : System.Configuration.ConfigurationElement" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SharedAccessSignatureElement extends System.Configuration.ConfigurationElement" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.NotificationHubs.Configuration.SharedAccessSignatureElement" />
  <TypeSignature Language="VB.NET" Value="Public Class SharedAccessSignatureElement&#xA;Inherits ConfigurationElement" />
  <TypeSignature Language="F#" Value="type SharedAccessSignatureElement = class&#xA;    inherit ConfigurationElement" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.16.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Configuration.ConfigurationElement</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="a1e7c-101">共有アクセス署名の要素を表します。</span><span class="sxs-lookup"><span data-stu-id="a1e7c-101">Represents a shared access signature element.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CopyFrom">
      <MemberSignature Language="C#" Value="public void CopyFrom (Microsoft.Azure.NotificationHubs.Configuration.SharedAccessSignatureElement source);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void CopyFrom(class Microsoft.Azure.NotificationHubs.Configuration.SharedAccessSignatureElement source) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.Configuration.SharedAccessSignatureElement.CopyFrom(Microsoft.Azure.NotificationHubs.Configuration.SharedAccessSignatureElement)" />
      <MemberSignature Language="VB.NET" Value="Public Sub CopyFrom (source As SharedAccessSignatureElement)" />
      <MemberSignature Language="F#" Value="member this.CopyFrom : Microsoft.Azure.NotificationHubs.Configuration.SharedAccessSignatureElement -&gt; unit" Usage="sharedAccessSignatureElement.CopyFrom source" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="source" Type="Microsoft.Azure.NotificationHubs.Configuration.SharedAccessSignatureElement" />
      </Parameters>
      <Docs>
        <param name="source"><span data-ttu-id="a1e7c-102">内容をコピーするソース。</span><span class="sxs-lookup"><span data-stu-id="a1e7c-102">The source to copy the contents from.</span></span></param>
        <summary><span data-ttu-id="a1e7c-103">この構成要素から指定した要素をコピーします。</span><span class="sxs-lookup"><span data-stu-id="a1e7c-103">Copies the specified element from this configuration element.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Key">
      <MemberSignature Language="C#" Value="public string Key { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Key" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.Configuration.SharedAccessSignatureElement.Key" />
      <MemberSignature Language="VB.NET" Value="Public Property Key As String" />
      <MemberSignature Language="F#" Value="member this.Key : string with get, set" Usage="Microsoft.Azure.NotificationHubs.Configuration.SharedAccessSignatureElement.Key" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
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
        <summary><span data-ttu-id="a1e7c-104">取得または共有アクセス キーを設定します。</span><span class="sxs-lookup"><span data-stu-id="a1e7c-104">Gets or sets the shared access key.</span></span></summary>
        <value><span data-ttu-id="a1e7c-105">共有アクセス キー。</span><span class="sxs-lookup"><span data-stu-id="a1e7c-105">The shared access key.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeyName">
      <MemberSignature Language="C#" Value="public string KeyName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string KeyName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.Configuration.SharedAccessSignatureElement.KeyName" />
      <MemberSignature Language="VB.NET" Value="Public Property KeyName As String" />
      <MemberSignature Language="F#" Value="member this.KeyName : string with get, set" Usage="Microsoft.Azure.NotificationHubs.Configuration.SharedAccessSignatureElement.KeyName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
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
        <summary><span data-ttu-id="a1e7c-106">取得または共有アクセス キーの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="a1e7c-106">Gets or sets the shared access key name.</span></span></summary>
        <value><span data-ttu-id="a1e7c-107">共有アクセス キーの名前。</span><span class="sxs-lookup"><span data-stu-id="a1e7c-107">The shared access key name.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="protected override System.Configuration.ConfigurationPropertyCollection Properties { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Configuration.ConfigurationPropertyCollection Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.Configuration.SharedAccessSignatureElement.Properties" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides ReadOnly Property Properties As ConfigurationPropertyCollection" />
      <MemberSignature Language="F#" Value="member this.Properties : System.Configuration.ConfigurationPropertyCollection" Usage="Microsoft.Azure.NotificationHubs.Configuration.SharedAccessSignatureElement.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Configuration.ConfigurationPropertyCollection</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="a1e7c-108">構成プロパティのコレクションを取得します。</span><span class="sxs-lookup"><span data-stu-id="a1e7c-108">Gets the collection of configuration properties.</span></span></summary>
        <value><span data-ttu-id="a1e7c-109">構成プロパティのコレクション。</span><span class="sxs-lookup"><span data-stu-id="a1e7c-109">The collection of configuration properties.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TokenScope">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.NotificationHubs.TokenScope TokenScope { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.NotificationHubs.TokenScope TokenScope" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.Configuration.SharedAccessSignatureElement.TokenScope" />
      <MemberSignature Language="VB.NET" Value="Public Property TokenScope As TokenScope" />
      <MemberSignature Language="F#" Value="member this.TokenScope : Microsoft.Azure.NotificationHubs.TokenScope with get, set" Usage="Microsoft.Azure.NotificationHubs.Configuration.SharedAccessSignatureElement.TokenScope" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("tokenScope", DefaultValue=Mono.Cecil.CustomAttributeArgument, IsRequired=false)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.TokenScope</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="a1e7c-110">取得または要素に関連付けられているトークンのスコープを設定します。</span><span class="sxs-lookup"><span data-stu-id="a1e7c-110">Gets or sets the token scope associated with the element.</span></span></summary>
        <value><span data-ttu-id="a1e7c-111">要素に関連付けられているトークンのスコープです。</span><span class="sxs-lookup"><span data-stu-id="a1e7c-111">The token scope associated with the element.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>