<Type Name="StartStreamingJobParameters" FullName="Microsoft.Azure.Management.StreamAnalytics.Models.StartStreamingJobParameters">
  <TypeSignature Language="C#" Value="public class StartStreamingJobParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit StartStreamingJobParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StreamAnalytics.Models.StartStreamingJobParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class StartStreamingJobParameters" />
  <TypeSignature Language="F#" Value="type StartStreamingJobParameters = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            パラメーターは、ストリーミング ジョブの開始操作に指定します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StartStreamingJobParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.StartStreamingJobParameters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            StartStreamingJobParameters クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StartStreamingJobParameters (string outputStartMode = null, Nullable&lt;DateTime&gt; outputStartTime = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string outputStartMode, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; outputStartTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.StartStreamingJobParameters.#ctor(System.String,System.Nullable{System.DateTime})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional outputStartMode As String = null, Optional outputStartTime As Nullable(Of DateTime) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StreamAnalytics.Models.StartStreamingJobParameters : string * Nullable&lt;DateTime&gt; -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.StartStreamingJobParameters" Usage="new Microsoft.Azure.Management.StreamAnalytics.Models.StartStreamingJobParameters (outputStartMode, outputStartTime)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="outputStartMode" Type="System.String" />
        <Parameter Name="outputStartTime" Type="System.Nullable&lt;System.DateTime&gt;" />
      </Parameters>
      <Docs>
        <param name="outputStartMode">値は JobStartTime、CustomTime、または lastoutputeventtime ですジョブを起動するたびに、出力イベント ストリームの開始位置を開始する必要がありますかどうかを示すためにあります outputStartTime プロパティを介して指定されたカスタム ユーザー タイムスタンプで開始 またはから開始します。最後のイベントは、時間を出力します。
            使用可能な値が含まれます: 'JobStartTime'、'CustomTime'、'LastOutputEventTime'</param>
        <param name="outputStartTime">値がいずれか、ISO 8601 形式のタイムスタンプを出力イベント ストリームの開始位置を示すか、出力イベント ストリームが開始されていることを示す null をするたびに、ストリーミング ジョブが開始します。 このプロパティは、outputStartMode が CustomTime に設定されている場合、値にすることが必要です。</param>
        <summary>
            StartStreamingJobParameters クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OutputStartMode">
      <MemberSignature Language="C#" Value="public string OutputStartMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string OutputStartMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.StartStreamingJobParameters.OutputStartMode" />
      <MemberSignature Language="VB.NET" Value="Public Property OutputStartMode As String" />
      <MemberSignature Language="F#" Value="member this.OutputStartMode : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.StartStreamingJobParameters.OutputStartMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="outputStartMode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定の値は JobStartTime、CustomTime、または lastoutputeventtime ですジョブを起動するたびに、出力イベント ストリームの開始位置を開始する必要がありますかどうかを示す可能性がありますが、outputStartTime プロパティを介して指定されたカスタム ユーザー タイムスタンプで開始または。最後のイベント出力時刻から開始します。 使用可能な値が含まれます: 'JobStartTime'、'CustomTime'、'LastOutputEventTime'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OutputStartTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; OutputStartTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; OutputStartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.StartStreamingJobParameters.OutputStartTime" />
      <MemberSignature Language="VB.NET" Value="Public Property OutputStartTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.OutputStartTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.StartStreamingJobParameters.OutputStartTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="outputStartTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定の値がいずれか、ISO 8601 形式のタイムスタンプを出力イベント ストリームの開始位置を示すか、出力イベント ストリームが開始されていることを示す null をするたびに、ストリーミング ジョブが開始します。 このプロパティは、outputStartMode が CustomTime に設定されている場合、値にすることが必要です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>