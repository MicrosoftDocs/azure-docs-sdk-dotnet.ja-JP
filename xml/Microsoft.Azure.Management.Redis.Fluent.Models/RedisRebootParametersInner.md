<Type Name="RedisRebootParametersInner" FullName="Microsoft.Azure.Management.Redis.Fluent.Models.RedisRebootParametersInner">
  <TypeSignature Language="C#" Value="public class RedisRebootParametersInner" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RedisRebootParametersInner extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Redis.Fluent.Models.RedisRebootParametersInner" />
  <TypeSignature Language="VB.NET" Value="Public Class RedisRebootParametersInner" />
  <TypeSignature Language="F#" Value="type RedisRebootParametersInner = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="535dc-101">ノードを再起動する Redis を指定します。</span><span class="sxs-lookup"><span data-stu-id="535dc-101">Specifies which Redis node(s) to reboot.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RedisRebootParametersInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.Models.RedisRebootParametersInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="535dc-102">RedisRebootParametersInner クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="535dc-102">Initializes a new instance of the RedisRebootParametersInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RedisRebootParametersInner (string rebootType, Nullable&lt;int&gt; shardId = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string rebootType, valuetype System.Nullable`1&lt;int32&gt; shardId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.Models.RedisRebootParametersInner.#ctor(System.String,System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (rebootType As String, Optional shardId As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Redis.Fluent.Models.RedisRebootParametersInner : string * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Management.Redis.Fluent.Models.RedisRebootParametersInner" Usage="new Microsoft.Azure.Management.Redis.Fluent.Models.RedisRebootParametersInner (rebootType, shardId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="rebootType" Type="System.String" />
        <Parameter Name="shardId" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="rebootType"><span data-ttu-id="535dc-103">再起動する Redis ノードがどのです。</span><span class="sxs-lookup"><span data-stu-id="535dc-103">Which Redis node(s) to reboot.</span></span> <span data-ttu-id="535dc-104">この値によってデータ損失が発生します。</span><span class="sxs-lookup"><span data-stu-id="535dc-104">Depending on this value data loss is possible.</span></span> <span data-ttu-id="535dc-105">使用可能な値が含まれます: 'PrimaryNode'、'SecondaryNode'、'AllNodes'</span><span class="sxs-lookup"><span data-stu-id="535dc-105">Possible values include: 'PrimaryNode', 'SecondaryNode', 'AllNodes'</span></span></param>
        <param name="shardId"><span data-ttu-id="535dc-106">クラスタ リングが有効になっている場合、シャードの ID を再起動します。</span><span class="sxs-lookup"><span data-stu-id="535dc-106">If clustering is enabled, the ID of the shard to be rebooted.</span></span></param>
        <summary>
            <span data-ttu-id="535dc-107">RedisRebootParametersInner クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="535dc-107">Initializes a new instance of the RedisRebootParametersInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RebootType">
      <MemberSignature Language="C#" Value="public string RebootType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RebootType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Redis.Fluent.Models.RedisRebootParametersInner.RebootType" />
      <MemberSignature Language="VB.NET" Value="Public Property RebootType As String" />
      <MemberSignature Language="F#" Value="member this.RebootType : string with get, set" Usage="Microsoft.Azure.Management.Redis.Fluent.Models.RedisRebootParametersInner.RebootType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="535dc-108">取得またはノードを再起動する Redis を設定します。</span><span class="sxs-lookup"><span data-stu-id="535dc-108">Gets or sets which Redis node(s) to reboot.</span></span> <span data-ttu-id="535dc-109">この値によってデータ損失が発生します。</span><span class="sxs-lookup"><span data-stu-id="535dc-109">Depending on this value data loss is possible.</span></span> <span data-ttu-id="535dc-110">使用可能な値が含まれます: 'PrimaryNode'、'SecondaryNode'、'AllNodes'</span><span class="sxs-lookup"><span data-stu-id="535dc-110">Possible values include: 'PrimaryNode', 'SecondaryNode', 'AllNodes'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ShardId">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; ShardId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; ShardId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Redis.Fluent.Models.RedisRebootParametersInner.ShardId" />
      <MemberSignature Language="VB.NET" Value="Public Property ShardId As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.ShardId : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Redis.Fluent.Models.RedisRebootParametersInner.ShardId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="535dc-111">取得または設定のクラスタ リングが有効になっている場合、シャードの ID を再起動します。</span><span class="sxs-lookup"><span data-stu-id="535dc-111">Gets or sets if clustering is enabled, the ID of the shard to be rebooted.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.Models.RedisRebootParametersInner.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="redisRebootParametersInner.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="535dc-112">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="535dc-112">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="535dc-113">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="535dc-113">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>