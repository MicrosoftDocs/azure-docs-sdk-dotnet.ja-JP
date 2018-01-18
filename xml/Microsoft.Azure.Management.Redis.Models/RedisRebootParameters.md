<Type Name="RedisRebootParameters" FullName="Microsoft.Azure.Management.Redis.Models.RedisRebootParameters">
  <TypeSignature Language="C#" Value="public class RedisRebootParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RedisRebootParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Redis.Models.RedisRebootParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class RedisRebootParameters" />
  <TypeSignature Language="F#" Value="type RedisRebootParameters = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="f22ee-101">ノードを再起動する Redis を指定します。</span><span class="sxs-lookup"><span data-stu-id="f22ee-101">Specifies which Redis node(s) to reboot.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RedisRebootParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Models.RedisRebootParameters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f22ee-102">RedisRebootParameters クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="f22ee-102">Initializes a new instance of the RedisRebootParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RedisRebootParameters (string rebootType, Nullable&lt;int&gt; shardId = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string rebootType, valuetype System.Nullable`1&lt;int32&gt; shardId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Models.RedisRebootParameters.#ctor(System.String,System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (rebootType As String, Optional shardId As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Redis.Models.RedisRebootParameters : string * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Management.Redis.Models.RedisRebootParameters" Usage="new Microsoft.Azure.Management.Redis.Models.RedisRebootParameters (rebootType, shardId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="rebootType" Type="System.String" />
        <Parameter Name="shardId" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="rebootType"><span data-ttu-id="f22ee-103">再起動する Redis ノードがどのです。</span><span class="sxs-lookup"><span data-stu-id="f22ee-103">Which Redis node(s) to reboot.</span></span> <span data-ttu-id="f22ee-104">この値によってデータ損失が発生します。</span><span class="sxs-lookup"><span data-stu-id="f22ee-104">Depending on this value data loss is possible.</span></span> <span data-ttu-id="f22ee-105">使用可能な値が含まれます: 'PrimaryNode'、'SecondaryNode'、'AllNodes'</span><span class="sxs-lookup"><span data-stu-id="f22ee-105">Possible values include: 'PrimaryNode', 'SecondaryNode', 'AllNodes'</span></span></param>
        <param name="shardId"><span data-ttu-id="f22ee-106">クラスタ リングが有効になっている場合、シャードの ID を再起動します。</span><span class="sxs-lookup"><span data-stu-id="f22ee-106">If clustering is enabled, the ID of the shard to be rebooted.</span></span></param>
        <summary>
            <span data-ttu-id="f22ee-107">RedisRebootParameters クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="f22ee-107">Initializes a new instance of the RedisRebootParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RebootType">
      <MemberSignature Language="C#" Value="public string RebootType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RebootType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Redis.Models.RedisRebootParameters.RebootType" />
      <MemberSignature Language="VB.NET" Value="Public Property RebootType As String" />
      <MemberSignature Language="F#" Value="member this.RebootType : string with get, set" Usage="Microsoft.Azure.Management.Redis.Models.RedisRebootParameters.RebootType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="rebootType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f22ee-108">取得またはノードを再起動する Redis を設定します。</span><span class="sxs-lookup"><span data-stu-id="f22ee-108">Gets or sets which Redis node(s) to reboot.</span></span> <span data-ttu-id="f22ee-109">この値によってデータ損失が発生します。</span><span class="sxs-lookup"><span data-stu-id="f22ee-109">Depending on this value data loss is possible.</span></span> <span data-ttu-id="f22ee-110">使用可能な値が含まれます: 'PrimaryNode'、'SecondaryNode'、'AllNodes'</span><span class="sxs-lookup"><span data-stu-id="f22ee-110">Possible values include: 'PrimaryNode', 'SecondaryNode', 'AllNodes'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ShardId">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; ShardId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; ShardId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Redis.Models.RedisRebootParameters.ShardId" />
      <MemberSignature Language="VB.NET" Value="Public Property ShardId As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.ShardId : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Redis.Models.RedisRebootParameters.ShardId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="shardId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f22ee-111">取得または設定のクラスタ リングが有効になっている場合、シャードの ID を再起動します。</span><span class="sxs-lookup"><span data-stu-id="f22ee-111">Gets or sets if clustering is enabled, the ID of the shard to be rebooted.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Models.RedisRebootParameters.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="redisRebootParameters.Validate " />
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
            <span data-ttu-id="f22ee-112">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="f22ee-112">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f22ee-113">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f22ee-113">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>