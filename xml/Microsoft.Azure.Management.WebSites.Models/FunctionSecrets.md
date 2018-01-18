<Type Name="FunctionSecrets" FullName="Microsoft.Azure.Management.WebSites.Models.FunctionSecrets">
  <TypeSignature Language="C#" Value="public class FunctionSecrets : Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit FunctionSecrets extends Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.FunctionSecrets" />
  <TypeSignature Language="VB.NET" Value="Public Class FunctionSecrets&#xA;Inherits ProxyOnlyResource" />
  <TypeSignature Language="F#" Value="type FunctionSecrets = class&#xA;    inherit ProxyOnlyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="657f7-101">関数のシークレット。</span><span class="sxs-lookup"><span data-stu-id="657f7-101">Function secrets.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FunctionSecrets ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.FunctionSecrets.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="657f7-102">FunctionSecrets クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="657f7-102">Initializes a new instance of the FunctionSecrets class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FunctionSecrets (string id = null, string name = null, string kind = null, string type = null, string key = null, string triggerUrl = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string kind, string type, string key, string triggerUrl) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.FunctionSecrets.#ctor(System.String,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional kind As String = null, Optional type As String = null, Optional key As String = null, Optional triggerUrl As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.FunctionSecrets : string * string * string * string * string * string -&gt; Microsoft.Azure.Management.WebSites.Models.FunctionSecrets" Usage="new Microsoft.Azure.Management.WebSites.Models.FunctionSecrets (id, name, kind, type, key, triggerUrl)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="kind" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="key" Type="System.String" />
        <Parameter Name="triggerUrl" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="657f7-103">リソース id です。</span><span class="sxs-lookup"><span data-stu-id="657f7-103">Resource Id.</span></span></param>
        <param name="name"><span data-ttu-id="657f7-104">リソースの名前です。</span><span class="sxs-lookup"><span data-stu-id="657f7-104">Resource Name.</span></span></param>
        <param name="kind"><span data-ttu-id="657f7-105">リソースの種類。</span><span class="sxs-lookup"><span data-stu-id="657f7-105">Kind of resource.</span></span></param>
        <param name="type"><span data-ttu-id="657f7-106">リソースの種類。</span><span class="sxs-lookup"><span data-stu-id="657f7-106">Resource type.</span></span></param>
        <param name="key"><span data-ttu-id="657f7-107">秘密キーです。</span><span class="sxs-lookup"><span data-stu-id="657f7-107">Secret key.</span></span></param>
        <param name="triggerUrl"><span data-ttu-id="657f7-108">トリガーの URL です。</span><span class="sxs-lookup"><span data-stu-id="657f7-108">Trigger URL.</span></span></param>
        <summary>
            <span data-ttu-id="657f7-109">FunctionSecrets クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="657f7-109">Initializes a new instance of the FunctionSecrets class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Key">
      <MemberSignature Language="C#" Value="public string Key { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Key" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.FunctionSecrets.Key" />
      <MemberSignature Language="VB.NET" Value="Public Property Key As String" />
      <MemberSignature Language="F#" Value="member this.Key : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.FunctionSecrets.Key" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.key")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="657f7-110">取得または秘密キーを設定します。</span><span class="sxs-lookup"><span data-stu-id="657f7-110">Gets or sets secret key.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TriggerUrl">
      <MemberSignature Language="C#" Value="public string TriggerUrl { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TriggerUrl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.FunctionSecrets.TriggerUrl" />
      <MemberSignature Language="VB.NET" Value="Public Property TriggerUrl As String" />
      <MemberSignature Language="F#" Value="member this.TriggerUrl : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.FunctionSecrets.TriggerUrl" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.triggerUrl")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="657f7-111">取得またはトリガーの URL を設定します。</span><span class="sxs-lookup"><span data-stu-id="657f7-111">Gets or sets trigger URL.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>