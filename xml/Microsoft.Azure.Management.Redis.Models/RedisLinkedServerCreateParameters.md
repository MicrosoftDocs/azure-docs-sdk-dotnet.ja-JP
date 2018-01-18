<Type Name="RedisLinkedServerCreateParameters" FullName="Microsoft.Azure.Management.Redis.Models.RedisLinkedServerCreateParameters">
  <TypeSignature Language="C#" Value="public class RedisLinkedServerCreateParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RedisLinkedServerCreateParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Redis.Models.RedisLinkedServerCreateParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class RedisLinkedServerCreateParameters" />
  <TypeSignature Language="F#" Value="type RedisLinkedServerCreateParameters = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="3d714-101">Redis キャッシュに、リンク サーバーを作成するために必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="3d714-101">Parameter required for creating a linked server to redis cache.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RedisLinkedServerCreateParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Models.RedisLinkedServerCreateParameters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="3d714-102">RedisLinkedServerCreateParameters クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="3d714-102">Initializes a new instance of the RedisLinkedServerCreateParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RedisLinkedServerCreateParameters (string linkedRedisCacheId, string linkedRedisCacheLocation, Microsoft.Azure.Management.Redis.Models.ReplicationRole serverRole);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string linkedRedisCacheId, string linkedRedisCacheLocation, valuetype Microsoft.Azure.Management.Redis.Models.ReplicationRole serverRole) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Models.RedisLinkedServerCreateParameters.#ctor(System.String,System.String,Microsoft.Azure.Management.Redis.Models.ReplicationRole)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (linkedRedisCacheId As String, linkedRedisCacheLocation As String, serverRole As ReplicationRole)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Redis.Models.RedisLinkedServerCreateParameters : string * string * Microsoft.Azure.Management.Redis.Models.ReplicationRole -&gt; Microsoft.Azure.Management.Redis.Models.RedisLinkedServerCreateParameters" Usage="new Microsoft.Azure.Management.Redis.Models.RedisLinkedServerCreateParameters (linkedRedisCacheId, linkedRedisCacheLocation, serverRole)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="linkedRedisCacheId" Type="System.String" />
        <Parameter Name="linkedRedisCacheLocation" Type="System.String" />
        <Parameter Name="serverRole" Type="Microsoft.Azure.Management.Redis.Models.ReplicationRole" />
      </Parameters>
      <Docs>
        <param name="linkedRedisCacheId"><span data-ttu-id="3d714-103">リンク redis cache の完全修飾リソース Id。</span><span class="sxs-lookup"><span data-stu-id="3d714-103">Fully qualified resourceId of the linked redis cache.</span></span></param>
        <param name="linkedRedisCacheLocation"><span data-ttu-id="3d714-104">リンクされた redis キャッシュの場所です。</span><span class="sxs-lookup"><span data-stu-id="3d714-104">Location of the linked redis cache.</span></span></param>
        <param name="serverRole"><span data-ttu-id="3d714-105">リンク サーバーの役割。</span><span class="sxs-lookup"><span data-stu-id="3d714-105">Role of the linked server.</span></span> <span data-ttu-id="3d714-106">使用可能な値が含まれます 'Primary'、'セカンダリ'。</span><span class="sxs-lookup"><span data-stu-id="3d714-106">Possible values include: 'Primary', 'Secondary'</span></span></param>
        <summary>
            <span data-ttu-id="3d714-107">RedisLinkedServerCreateParameters クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="3d714-107">Initializes a new instance of the RedisLinkedServerCreateParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LinkedRedisCacheId">
      <MemberSignature Language="C#" Value="public string LinkedRedisCacheId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LinkedRedisCacheId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Redis.Models.RedisLinkedServerCreateParameters.LinkedRedisCacheId" />
      <MemberSignature Language="VB.NET" Value="Public Property LinkedRedisCacheId As String" />
      <MemberSignature Language="F#" Value="member this.LinkedRedisCacheId : string with get, set" Usage="Microsoft.Azure.Management.Redis.Models.RedisLinkedServerCreateParameters.LinkedRedisCacheId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.linkedRedisCacheId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3d714-108">取得またはリンクされた redis cache の完全修飾リソース Id を設定します。</span><span class="sxs-lookup"><span data-stu-id="3d714-108">Gets or sets fully qualified resourceId of the linked redis cache.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LinkedRedisCacheLocation">
      <MemberSignature Language="C#" Value="public string LinkedRedisCacheLocation { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LinkedRedisCacheLocation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Redis.Models.RedisLinkedServerCreateParameters.LinkedRedisCacheLocation" />
      <MemberSignature Language="VB.NET" Value="Public Property LinkedRedisCacheLocation As String" />
      <MemberSignature Language="F#" Value="member this.LinkedRedisCacheLocation : string with get, set" Usage="Microsoft.Azure.Management.Redis.Models.RedisLinkedServerCreateParameters.LinkedRedisCacheLocation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.linkedRedisCacheLocation")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3d714-109">取得またはリンクされた redis キャッシュの場所を設定します。</span><span class="sxs-lookup"><span data-stu-id="3d714-109">Gets or sets location of the linked redis cache.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServerRole">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Redis.Models.ReplicationRole ServerRole { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Redis.Models.ReplicationRole ServerRole" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Redis.Models.RedisLinkedServerCreateParameters.ServerRole" />
      <MemberSignature Language="VB.NET" Value="Public Property ServerRole As ReplicationRole" />
      <MemberSignature Language="F#" Value="member this.ServerRole : Microsoft.Azure.Management.Redis.Models.ReplicationRole with get, set" Usage="Microsoft.Azure.Management.Redis.Models.RedisLinkedServerCreateParameters.ServerRole" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.serverRole")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Redis.Models.ReplicationRole</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3d714-110">取得またはリンク サーバーの役割を設定します。</span><span class="sxs-lookup"><span data-stu-id="3d714-110">Gets or sets role of the linked server.</span></span> <span data-ttu-id="3d714-111">使用可能な値が含まれます 'Primary'、'セカンダリ'。</span><span class="sxs-lookup"><span data-stu-id="3d714-111">Possible values include: 'Primary', 'Secondary'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Models.RedisLinkedServerCreateParameters.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="redisLinkedServerCreateParameters.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="3d714-112">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="3d714-112">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="3d714-113">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="3d714-113">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>