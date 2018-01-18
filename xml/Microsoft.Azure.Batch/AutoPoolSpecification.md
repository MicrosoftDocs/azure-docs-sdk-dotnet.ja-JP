<Type Name="AutoPoolSpecification" FullName="Microsoft.Azure.Batch.AutoPoolSpecification">
  <TypeSignature Language="C#" Value="public class AutoPoolSpecification" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AutoPoolSpecification extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.AutoPoolSpecification" />
  <TypeSignature Language="VB.NET" Value="Public Class AutoPoolSpecification" />
  <TypeSignature Language="F#" Value="type AutoPoolSpecification = class&#xA;    interface ITransportObjectProvider&lt;AutoPoolSpecification&gt;&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="d1656-101">一時 '自動プール' の特性を指定します。</span><span class="sxs-lookup"><span data-stu-id="d1656-101">Specifies characteristics for a temporary 'auto pool'.</span></span> <span data-ttu-id="d1656-102">バッチ サービスはこの自動プールを作成には、ジョブのすべてのタスクを実行し、既定では、ジョブが完了した後にプールを削除します。</span><span class="sxs-lookup"><span data-stu-id="d1656-102">The Batch service will create this auto pool, run all the tasks for the job on it, and by default delete the pool once the job has completed.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AutoPoolSpecification ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.AutoPoolSpecification.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="d1656-103"><see cref="T:Microsoft.Azure.Batch.AutoPoolSpecification" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="d1656-103">Initializes a new instance of the <see cref="T:Microsoft.Azure.Batch.AutoPoolSpecification" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AutoPoolIdPrefix">
      <MemberSignature Language="C#" Value="public string AutoPoolIdPrefix { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AutoPoolIdPrefix" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.AutoPoolSpecification.AutoPoolIdPrefix" />
      <MemberSignature Language="VB.NET" Value="Public Property AutoPoolIdPrefix As String" />
      <MemberSignature Language="F#" Value="member this.AutoPoolIdPrefix : string with get, set" Usage="Microsoft.Azure.Batch.AutoPoolSpecification.AutoPoolIdPrefix" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d1656-104">取得またはプールが自動的に作成された一意の識別子を追加するプレフィックスを設定します。</span><span class="sxs-lookup"><span data-stu-id="d1656-104">Gets or sets a prefix to be added to the unique identifier when a pool is automatically created.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="d1656-105">プレフィックスは省略できます。</span><span class="sxs-lookup"><span data-stu-id="d1656-105">The prefix is optional.</span></span> <span data-ttu-id="d1656-106">存在する場合、長さは 20 文字まで指定でき、id (英数字、ハイフンとアンダー スコアのみ) の通常の規則に従う必要があります。</span><span class="sxs-lookup"><span data-stu-id="d1656-106">If present, it can be up to 20 characters long and must adhere to the usual rules for ids (alphanumeric characters, hyphens and underscores only).</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="KeepAlive">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; KeepAlive { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; KeepAlive" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.AutoPoolSpecification.KeepAlive" />
      <MemberSignature Language="VB.NET" Value="Public Property KeepAlive As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.KeepAlive : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Batch.AutoPoolSpecification.KeepAlive" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d1656-107">取得または設定した後、自動プールを維持するかどうか、<see cref="P:Microsoft.Azure.Batch.AutoPoolSpecification.PoolLifetimeOption" />有効期限が切れた。</span><span class="sxs-lookup"><span data-stu-id="d1656-107">Gets or sets whether to keep the auto pool alive after its <see cref="P:Microsoft.Azure.Batch.AutoPoolSpecification.PoolLifetimeOption" /> expires.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="d1656-108">既定値は false です。</span><span class="sxs-lookup"><span data-stu-id="d1656-108">The default value is false.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PoolLifetimeOption">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Common.PoolLifetimeOption PoolLifetimeOption { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Batch.Common.PoolLifetimeOption PoolLifetimeOption" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.AutoPoolSpecification.PoolLifetimeOption" />
      <MemberSignature Language="VB.NET" Value="Public Property PoolLifetimeOption As PoolLifetimeOption" />
      <MemberSignature Language="F#" Value="member this.PoolLifetimeOption : Microsoft.Azure.Batch.Common.PoolLifetimeOption with get, set" Usage="Microsoft.Azure.Batch.AutoPoolSpecification.PoolLifetimeOption" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.PoolLifetimeOption</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d1656-109">取得または作成した自動プール、およびスケジュールで複数のジョブ プールに割り当てられたの最小有効期間を設定します。</span><span class="sxs-lookup"><span data-stu-id="d1656-109">Gets or sets the minimum lifetime of created auto pools, and how multiple jobs on a schedule are assigned to pools.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="d1656-110">場合、自動プールがその PoolLifetimeOption よりも長く live 可能性があります<see cref="P:Microsoft.Azure.Batch.AutoPoolSpecification.KeepAlive" />が設定されています。</span><span class="sxs-lookup"><span data-stu-id="d1656-110">An auto pool may live longer than its PoolLifetimeOption if <see cref="P:Microsoft.Azure.Batch.AutoPoolSpecification.KeepAlive" /> is set.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PoolSpecification">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.PoolSpecification PoolSpecification { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.PoolSpecification PoolSpecification" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.AutoPoolSpecification.PoolSpecification" />
      <MemberSignature Language="VB.NET" Value="Public Property PoolSpecification As PoolSpecification" />
      <MemberSignature Language="F#" Value="member this.PoolSpecification : Microsoft.Azure.Batch.PoolSpecification with get, set" Usage="Microsoft.Azure.Batch.AutoPoolSpecification.PoolSpecification" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.PoolSpecification</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d1656-111">取得または自動プールのプール仕様を設定します。</span><span class="sxs-lookup"><span data-stu-id="d1656-111">Gets or sets the pool specification for the auto pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>