<Type Name="SBAuthorizationRule" FullName="Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule">
  <TypeSignature Language="C#" Value="public class SBAuthorizationRule : Microsoft.Azure.Management.ServiceBus.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SBAuthorizationRule extends Microsoft.Azure.Management.ServiceBus.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule" />
  <TypeSignature Language="VB.NET" Value="Public Class SBAuthorizationRule&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type SBAuthorizationRule = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.ServiceBus.Models.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="9f0a5-101">名前空間の承認規則の説明です。</span><span class="sxs-lookup"><span data-stu-id="9f0a5-101">Description of a namespace authorization rule.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SBAuthorizationRule ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="9f0a5-102">SBAuthorizationRule クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="9f0a5-102">Initializes a new instance of the SBAuthorizationRule class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SBAuthorizationRule (System.Collections.Generic.IList&lt;Nullable&lt;Microsoft.Azure.Management.ServiceBus.Models.AccessRights&gt;&gt; rights, string id = null, string name = null, string type = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.ServiceBus.Models.AccessRights&gt;&gt; rights, string id, string name, string type) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule.#ctor(System.Collections.Generic.IList{System.Nullable{Microsoft.Azure.Management.ServiceBus.Models.AccessRights}},System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (rights As IList(Of Nullable(Of AccessRights)), Optional id As String = null, Optional name As String = null, Optional type As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule : System.Collections.Generic.IList&lt;Nullable&lt;Microsoft.Azure.Management.ServiceBus.Models.AccessRights&gt;&gt; * string * string * string -&gt; Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule" Usage="new Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule (rights, id, name, type)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="rights" Type="System.Collections.Generic.IList&lt;System.Nullable&lt;Microsoft.Azure.Management.ServiceBus.Models.AccessRights&gt;&gt;" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="rights"><span data-ttu-id="9f0a5-103">ルールに関連付けられている権限。</span><span class="sxs-lookup"><span data-stu-id="9f0a5-103">The rights associated with the rule.</span></span></param>
        <param name="id"><span data-ttu-id="9f0a5-104">リソース Id</span><span class="sxs-lookup"><span data-stu-id="9f0a5-104">Resource Id</span></span></param>
        <param name="name"><span data-ttu-id="9f0a5-105">リソース名</span><span class="sxs-lookup"><span data-stu-id="9f0a5-105">Resource name</span></span></param>
        <param name="type"><span data-ttu-id="9f0a5-106">リソースの種類</span><span class="sxs-lookup"><span data-stu-id="9f0a5-106">Resource type</span></span></param>
        <summary>
            <span data-ttu-id="9f0a5-107">SBAuthorizationRule クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="9f0a5-107">Initializes a new instance of the SBAuthorizationRule class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Rights">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Nullable&lt;Microsoft.Azure.Management.ServiceBus.Models.AccessRights&gt;&gt; Rights { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.ServiceBus.Models.AccessRights&gt;&gt; Rights" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule.Rights" />
      <MemberSignature Language="VB.NET" Value="Public Property Rights As IList(Of Nullable(Of AccessRights))" />
      <MemberSignature Language="F#" Value="member this.Rights : System.Collections.Generic.IList&lt;Nullable&lt;Microsoft.Azure.Management.ServiceBus.Models.AccessRights&gt;&gt; with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule.Rights" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.rights")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Nullable&lt;Microsoft.Azure.Management.ServiceBus.Models.AccessRights&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9f0a5-108">取得またはルールに関連付けられている権限を設定します。</span><span class="sxs-lookup"><span data-stu-id="9f0a5-108">Gets or sets the rights associated with the rule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="sBAuthorizationRule.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="9f0a5-109">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="9f0a5-109">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="9f0a5-110">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="9f0a5-110">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>