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
            結果とプールの自動スケール式の実行からのエラーです。
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
            AutoScaleRun クラスの新しいインスタンスを初期化します。
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
        <param name="evaluationTime">自動スケール式が最後に評価された時刻。</param>
        <param name="results">自動スケール式の評価に使用されるすべての変数の最終的な値です。</param>
        <param name="error">エラーの詳細が発生しました、プールで自動スケール式を評価する場合、評価に失敗しました。</param>
        <summary>
            AutoScaleRun クラスの新しいインスタンスを初期化します。
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
            取得または評価が成功した場合、エラーが発生しました、プールで自動スケール式の評価の詳細を設定します。
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
            取得または自動スケール式が最後に評価された時刻を設定します。
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
            取得または自動スケール式の評価に使用されるすべての変数の最終的な値を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            フォーム $variable に各変数の値が返されます = 値、および変数はセミコロンで区切って指定します。
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
            オブジェクトを検証します。
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            検証が失敗した場合にスローされます。
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>