<Type Name="AutoScaleRun" FullName="Microsoft.Azure.Batch.Protocol.Models.AutoScaleRun">
  <TypeSignature Language="C#" Value="public class AutoScaleRun" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AutoScaleRun extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.AutoScaleRun" />
  <TypeSignature Language="VB.NET" Value="Public Class AutoScaleRun" />
  <TypeSignature Language="F#" Value="type AutoScaleRun = class" />
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
            結果とプールの自動スケール式の実行からのエラーです。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AutoScaleRun ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.AutoScaleRun.#ctor" />
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
            AutoScaleRun クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AutoScaleRun (DateTime timestamp, string results = null, Microsoft.Azure.Batch.Protocol.Models.AutoScaleRunError error = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.DateTime timestamp, string results, class Microsoft.Azure.Batch.Protocol.Models.AutoScaleRunError error) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.AutoScaleRun.#ctor(System.DateTime,System.String,Microsoft.Azure.Batch.Protocol.Models.AutoScaleRunError)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (timestamp As DateTime, Optional results As String = null, Optional error As AutoScaleRunError = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.AutoScaleRun : DateTime * string * Microsoft.Azure.Batch.Protocol.Models.AutoScaleRunError -&gt; Microsoft.Azure.Batch.Protocol.Models.AutoScaleRun" Usage="new Microsoft.Azure.Batch.Protocol.Models.AutoScaleRun (timestamp, results, error)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="timestamp" Type="System.DateTime" />
        <Parameter Name="results" Type="System.String" />
        <Parameter Name="error" Type="Microsoft.Azure.Batch.Protocol.Models.AutoScaleRunError" />
      </Parameters>
      <Docs>
        <param name="timestamp">自動スケール式が最後に評価された時刻。</param>
        <param name="results">自動スケール式の評価に使用されるすべての変数の最終的な値です。</param>
        <param name="error">エラーの詳細が発生しました、プールで自動スケール式を評価する場合、評価に失敗しました。</param>
        <summary>
            AutoScaleRun クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Error">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.AutoScaleRunError Error { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.AutoScaleRunError Error" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.AutoScaleRun.Error" />
      <MemberSignature Language="VB.NET" Value="Public Property Error As AutoScaleRunError" />
      <MemberSignature Language="F#" Value="member this.Error : Microsoft.Azure.Batch.Protocol.Models.AutoScaleRunError with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.AutoScaleRun.Error" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="error")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.AutoScaleRunError</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または評価が成功した場合、エラーが発生しました、プールで自動スケール式の評価の詳細を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Results">
      <MemberSignature Language="C#" Value="public string Results { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Results" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.AutoScaleRun.Results" />
      <MemberSignature Language="VB.NET" Value="Public Property Results As String" />
      <MemberSignature Language="F#" Value="member this.Results : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.AutoScaleRun.Results" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
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
    <Member MemberName="Timestamp">
      <MemberSignature Language="C#" Value="public DateTime Timestamp { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime Timestamp" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.AutoScaleRun.Timestamp" />
      <MemberSignature Language="VB.NET" Value="Public Property Timestamp As DateTime" />
      <MemberSignature Language="F#" Value="member this.Timestamp : DateTime with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.AutoScaleRun.Timestamp" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="timestamp")</AttributeName>
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
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.AutoScaleRun.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="autoScaleRun.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
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