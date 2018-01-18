<Type Name="PoolEnableAutoScaleParameter" FullName="Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleParameter">
  <TypeSignature Language="C#" Value="public class PoolEnableAutoScaleParameter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PoolEnableAutoScaleParameter extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleParameter" />
  <TypeSignature Language="VB.NET" Value="Public Class PoolEnableAutoScaleParameter" />
  <TypeSignature Language="F#" Value="type PoolEnableAutoScaleParameter = class" />
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
            <span data-ttu-id="eaae9-101">プールの自動スケーリングを有効にするためのオプションです。</span><span class="sxs-lookup"><span data-stu-id="eaae9-101">Options for enabling automatic scaling on a pool.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PoolEnableAutoScaleParameter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleParameter.#ctor" />
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
            <span data-ttu-id="eaae9-102">PoolEnableAutoScaleParameter クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="eaae9-102">Initializes a new instance of the PoolEnableAutoScaleParameter class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PoolEnableAutoScaleParameter (string autoScaleFormula = null, Nullable&lt;TimeSpan&gt; autoScaleEvaluationInterval = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string autoScaleFormula, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; autoScaleEvaluationInterval) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleParameter.#ctor(System.String,System.Nullable{System.TimeSpan})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional autoScaleFormula As String = null, Optional autoScaleEvaluationInterval As Nullable(Of TimeSpan) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleParameter : string * Nullable&lt;TimeSpan&gt; -&gt; Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleParameter" Usage="new Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleParameter (autoScaleFormula, autoScaleEvaluationInterval)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="autoScaleFormula" Type="System.String" />
        <Parameter Name="autoScaleEvaluationInterval" Type="System.Nullable&lt;System.TimeSpan&gt;" />
      </Parameters>
      <Docs>
        <param name="autoScaleFormula"><span data-ttu-id="eaae9-103">プール内の計算ノードの必要な数の式。</span><span class="sxs-lookup"><span data-stu-id="eaae9-103">The formula for the desired number of compute nodes in the pool.</span></span></param>
        <param name="autoScaleEvaluationInterval"><span data-ttu-id="eaae9-104">自動スケールの数式に従ってプールのサイズを自動的に調整する時間間隔。</span><span class="sxs-lookup"><span data-stu-id="eaae9-104">The time interval at which to automatically adjust the pool size according to the autoscale formula.</span></span></param>
        <summary>
            <span data-ttu-id="eaae9-105">PoolEnableAutoScaleParameter クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="eaae9-105">Initializes a new instance of the PoolEnableAutoScaleParameter class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AutoScaleEvaluationInterval">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; AutoScaleEvaluationInterval { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; AutoScaleEvaluationInterval" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleParameter.AutoScaleEvaluationInterval" />
      <MemberSignature Language="VB.NET" Value="Public Property AutoScaleEvaluationInterval As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.AutoScaleEvaluationInterval : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleParameter.AutoScaleEvaluationInterval" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="autoScaleEvaluationInterval")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="eaae9-106">取得または自動スケールの数式に従ってプールのサイズを自動的に調整するための時間間隔を設定します。</span><span class="sxs-lookup"><span data-stu-id="eaae9-106">Gets or sets the time interval at which to automatically adjust the pool size according to the autoscale formula.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="eaae9-107">既定値は、15 分です。</span><span class="sxs-lookup"><span data-stu-id="eaae9-107">The default value is 15 minutes.</span></span> <span data-ttu-id="eaae9-108">最小値と最大値は、それぞれ 5 分と 168 時間です。</span><span class="sxs-lookup"><span data-stu-id="eaae9-108">The minimum and maximum value are 5 minutes and 168 hours respectively.</span></span> <span data-ttu-id="eaae9-109">小さい値 5 分 168 時間より大きいかを指定すると、バッチ サービスは無効なプロパティ値エラー; で要求を拒否します。REST API を直接呼び出すが、HTTP ステータス コードは 400 (Bad Request) がします。</span><span class="sxs-lookup"><span data-stu-id="eaae9-109">If you specify a value less than 5 minutes or greater than 168 hours, the Batch service rejects the request with an invalid property value error; if you are calling the REST API directly, the HTTP status code is 400 (Bad Request).</span></span> <span data-ttu-id="eaae9-110">新しい間隔を指定する場合、既存の自動スケールの評価スケジュールが停止し、新しい自動スケールの評価スケジュールが開始される、この要求の発行時の中、開始時刻を使用します。</span><span class="sxs-lookup"><span data-stu-id="eaae9-110">If you specify a new interval, then the existing autoscale evaluation schedule will be stopped and a new autoscale evaluation schedule will be started, with its starting time being the time when this request was issued.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="AutoScaleFormula">
      <MemberSignature Language="C#" Value="public string AutoScaleFormula { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AutoScaleFormula" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleParameter.AutoScaleFormula" />
      <MemberSignature Language="VB.NET" Value="Public Property AutoScaleFormula As String" />
      <MemberSignature Language="F#" Value="member this.AutoScaleFormula : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleParameter.AutoScaleFormula" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="autoScaleFormula")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="eaae9-111">取得またはプールに目的のコンピューティング ノードの数の式を設定します。</span><span class="sxs-lookup"><span data-stu-id="eaae9-111">Gets or sets the formula for the desired number of compute nodes in the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="eaae9-112">数式は、プールに適用される前に、有効性に対してチェックされます。</span><span class="sxs-lookup"><span data-stu-id="eaae9-112">The formula is checked for validity before it is applied to the pool.</span></span> <span data-ttu-id="eaae9-113">数式が有効でない場合、Batch service は詳細なエラー情報が要求を拒否します。</span><span class="sxs-lookup"><span data-stu-id="eaae9-113">If the formula is not valid, the Batch service rejects the request with detailed error information.</span></span> <span data-ttu-id="eaae9-114">この式の指定に関する詳細についてを参照して自動的に Azure Batch プール (https://azure.microsoft.com/en-us/documentation/articles/batch-automatic-scaling) 内のノードをコンピューティング スケール。</span><span class="sxs-lookup"><span data-stu-id="eaae9-114">For more information about specifying this formula, see Automatically scale compute nodes in an Azure Batch pool (https://azure.microsoft.com/en-us/documentation/articles/batch-automatic-scaling).</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>