<Type Name="AutoScaleRun" FullName="Microsoft.Azure.Management.Batch.Models.AutoScaleRun">
  <TypeSignature Language="C#" Value="public class AutoScaleRun" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AutoScaleRun extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Batch.Models.AutoScaleRun" />
  <TypeSignature Language="VB.NET" Value="Public Class AutoScaleRun" />
  <TypeSignature Language="F#" Value="type AutoScaleRun = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="9ac4d-101">結果とプールの自動スケール式の実行からのエラーです。</span><span class="sxs-lookup"><span data-stu-id="9ac4d-101">The results and errors from an execution of a pool autoscale formula.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AutoScaleRun ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.AutoScaleRun.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="9ac4d-102">AutoScaleRun クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="9ac4d-102">Initializes a new instance of the AutoScaleRun class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AutoScaleRun (DateTime evaluationTime, string results = null, Microsoft.Azure.Management.Batch.Models.AutoScaleRunError error = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.DateTime evaluationTime, string results, class Microsoft.Azure.Management.Batch.Models.AutoScaleRunError error) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.AutoScaleRun.#ctor(System.DateTime,System.String,Microsoft.Azure.Management.Batch.Models.AutoScaleRunError)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (evaluationTime As DateTime, Optional results As String = null, Optional error As AutoScaleRunError = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Batch.Models.AutoScaleRun : DateTime * string * Microsoft.Azure.Management.Batch.Models.AutoScaleRunError -&gt; Microsoft.Azure.Management.Batch.Models.AutoScaleRun" Usage="new Microsoft.Azure.Management.Batch.Models.AutoScaleRun (evaluationTime, results, error)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="evaluationTime" Type="System.DateTime" />
        <Parameter Name="results" Type="System.String" />
        <Parameter Name="error" Type="Microsoft.Azure.Management.Batch.Models.AutoScaleRunError" />
      </Parameters>
      <Docs>
        <param name="evaluationTime"><span data-ttu-id="9ac4d-103">自動スケール式が最後に評価された時刻。</span><span class="sxs-lookup"><span data-stu-id="9ac4d-103">The time at which the autoscale formula was last evaluated.</span></span></param>
        <param name="results"><span data-ttu-id="9ac4d-104">自動スケール式の評価に使用されるすべての変数の最終的な値です。</span><span class="sxs-lookup"><span data-stu-id="9ac4d-104">The final values of all variables used in the evaluation of the autoscale formula.</span></span></param>
        <param name="error"><span data-ttu-id="9ac4d-105">エラーの詳細が発生しました、プールで自動スケール式を評価する場合、評価に失敗しました。</span><span class="sxs-lookup"><span data-stu-id="9ac4d-105">Details of the error encountered evaluating the autoscale formula on the pool, if the evaluation was unsuccessful.</span></span></param>
        <summary>
            <span data-ttu-id="9ac4d-106">AutoScaleRun クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="9ac4d-106">Initializes a new instance of the AutoScaleRun class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Error">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Models.AutoScaleRunError Error { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Batch.Models.AutoScaleRunError Error" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.AutoScaleRun.Error" />
      <MemberSignature Language="VB.NET" Value="Public Property Error As AutoScaleRunError" />
      <MemberSignature Language="F#" Value="member this.Error : Microsoft.Azure.Management.Batch.Models.AutoScaleRunError with get, set" Usage="Microsoft.Azure.Management.Batch.Models.AutoScaleRun.Error" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="error")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.AutoScaleRunError</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9ac4d-107">取得または評価が成功した場合、エラーが発生しました、プールで自動スケール式の評価の詳細を設定します。</span><span class="sxs-lookup"><span data-stu-id="9ac4d-107">Gets or sets details of the error encountered evaluating the autoscale formula on the pool, if the evaluation was unsuccessful.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EvaluationTime">
      <MemberSignature Language="C#" Value="public DateTime EvaluationTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime EvaluationTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.AutoScaleRun.EvaluationTime" />
      <MemberSignature Language="VB.NET" Value="Public Property EvaluationTime As DateTime" />
      <MemberSignature Language="F#" Value="member this.EvaluationTime : DateTime with get, set" Usage="Microsoft.Azure.Management.Batch.Models.AutoScaleRun.EvaluationTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="evaluationTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9ac4d-108">取得または自動スケール式が最後に評価された時刻を設定します。</span><span class="sxs-lookup"><span data-stu-id="9ac4d-108">Gets or sets the time at which the autoscale formula was last evaluated.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Results">
      <MemberSignature Language="C#" Value="public string Results { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Results" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.AutoScaleRun.Results" />
      <MemberSignature Language="VB.NET" Value="Public Property Results As String" />
      <MemberSignature Language="F#" Value="member this.Results : string with get, set" Usage="Microsoft.Azure.Management.Batch.Models.AutoScaleRun.Results" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="results")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9ac4d-109">取得または自動スケール式の評価に使用されるすべての変数の最終的な値を設定します。</span><span class="sxs-lookup"><span data-stu-id="9ac4d-109">Gets or sets the final values of all variables used in the evaluation of the autoscale formula.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="9ac4d-110">フォーム $variable に各変数の値が返されます = 値、および変数はセミコロンで区切って指定します。</span><span class="sxs-lookup"><span data-stu-id="9ac4d-110">Each variable value is returned in the form $variable=value, and variables are separated by semicolons.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.AutoScaleRun.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="autoScaleRun.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="9ac4d-111">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="9ac4d-111">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="9ac4d-112">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="9ac4d-112">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>