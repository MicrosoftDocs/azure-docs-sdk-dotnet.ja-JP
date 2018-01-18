<Type Name="Permissions" FullName="Microsoft.Azure.Management.KeyVault.Models.Permissions">
  <TypeSignature Language="C#" Value="public class Permissions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Permissions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.KeyVault.Models.Permissions" />
  <TypeSignature Language="VB.NET" Value="Public Class Permissions" />
  <TypeSignature Language="F#" Value="type Permissions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.KeyVault</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="4d566-101">に対するアクセス許可 id がキー、秘密情報、証明書および記憶域。</span><span class="sxs-lookup"><span data-stu-id="4d566-101">Permissions the identity has for keys, secrets, certificates and storage.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Permissions ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.Models.Permissions.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="4d566-102">アクセス許可クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="4d566-102">Initializes a new instance of the Permissions class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Permissions (System.Collections.Generic.IList&lt;string&gt; keys = null, System.Collections.Generic.IList&lt;string&gt; secrets = null, System.Collections.Generic.IList&lt;string&gt; certificates = null, System.Collections.Generic.IList&lt;string&gt; storage = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;string&gt; keys, class System.Collections.Generic.IList`1&lt;string&gt; secrets, class System.Collections.Generic.IList`1&lt;string&gt; certificates, class System.Collections.Generic.IList`1&lt;string&gt; storage) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.Models.Permissions.#ctor(System.Collections.Generic.IList{System.String},System.Collections.Generic.IList{System.String},System.Collections.Generic.IList{System.String},System.Collections.Generic.IList{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional keys As IList(Of String) = null, Optional secrets As IList(Of String) = null, Optional certificates As IList(Of String) = null, Optional storage As IList(Of String) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.KeyVault.Models.Permissions : System.Collections.Generic.IList&lt;string&gt; * System.Collections.Generic.IList&lt;string&gt; * System.Collections.Generic.IList&lt;string&gt; * System.Collections.Generic.IList&lt;string&gt; -&gt; Microsoft.Azure.Management.KeyVault.Models.Permissions" Usage="new Microsoft.Azure.Management.KeyVault.Models.Permissions (keys, secrets, certificates, storage)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="keys" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="secrets" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="certificates" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="storage" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="keys"><span data-ttu-id="4d566-103">キーに対するアクセス許可</span><span class="sxs-lookup"><span data-stu-id="4d566-103">Permissions to keys</span></span></param>
        <param name="secrets"><span data-ttu-id="4d566-104">機密データへのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="4d566-104">Permissions to secrets</span></span></param>
        <param name="certificates"><span data-ttu-id="4d566-105">証明書へのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="4d566-105">Permissions to certificates</span></span></param>
        <param name="storage"><span data-ttu-id="4d566-106">ストレージ アカウントへのアクセス許可</span><span class="sxs-lookup"><span data-stu-id="4d566-106">Permissions to storage accounts</span></span></param>
        <summary>
            <span data-ttu-id="4d566-107">アクセス許可クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="4d566-107">Initializes a new instance of the Permissions class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Certificates">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Certificates { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Certificates" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.KeyVault.Models.Permissions.Certificates" />
      <MemberSignature Language="VB.NET" Value="Public Property Certificates As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Certificates : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.KeyVault.Models.Permissions.Certificates" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="certificates")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4d566-108">取得または証明書へのアクセス許可を設定</span><span class="sxs-lookup"><span data-stu-id="4d566-108">Gets or sets permissions to certificates</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Keys">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Keys { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Keys" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.KeyVault.Models.Permissions.Keys" />
      <MemberSignature Language="VB.NET" Value="Public Property Keys As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Keys : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.KeyVault.Models.Permissions.Keys" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="keys")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4d566-109">取得またはキーへのアクセス許可を設定</span><span class="sxs-lookup"><span data-stu-id="4d566-109">Gets or sets permissions to keys</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Secrets">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Secrets { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Secrets" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.KeyVault.Models.Permissions.Secrets" />
      <MemberSignature Language="VB.NET" Value="Public Property Secrets As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Secrets : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.KeyVault.Models.Permissions.Secrets" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="secrets")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4d566-110">取得または機密情報へのアクセス許可を設定</span><span class="sxs-lookup"><span data-stu-id="4d566-110">Gets or sets permissions to secrets</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Storage">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Storage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Storage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.KeyVault.Models.Permissions.Storage" />
      <MemberSignature Language="VB.NET" Value="Public Property Storage As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Storage : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.KeyVault.Models.Permissions.Storage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="storage")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4d566-111">取得またはストレージ アカウントへのアクセス許可を設定</span><span class="sxs-lookup"><span data-stu-id="4d566-111">Gets or sets permissions to storage accounts</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>