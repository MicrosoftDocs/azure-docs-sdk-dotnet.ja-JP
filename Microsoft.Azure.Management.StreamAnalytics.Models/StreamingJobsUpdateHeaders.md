<Type Name="StreamingJobsUpdateHeaders" FullName="Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJobsUpdateHeaders">
  <TypeSignature Language="C#" Value="public class StreamingJobsUpdateHeaders" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit StreamingJobsUpdateHeaders extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJobsUpdateHeaders" />
  <TypeSignature Language="VB.NET" Value="Public Class StreamingJobsUpdateHeaders" />
  <TypeSignature Language="F#" Value="type StreamingJobsUpdateHeaders = class" />
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
            更新操作のヘッダーを定義します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StreamingJobsUpdateHeaders ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJobsUpdateHeaders.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            StreamingJobsUpdateHeaders クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StreamingJobsUpdateHeaders (string eTag = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string eTag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJobsUpdateHeaders.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional eTag As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJobsUpdateHeaders : string -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJobsUpdateHeaders" Usage="new Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJobsUpdateHeaders eTag" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="eTag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="eTag">ストリーミング ジョブの現在のエンティティ タグ。
            これは、不透明な文字列です。 要求間でリソースが変更されたかどうかを検出するために使用できます。 使用することできますも、If-match または [なし]-If-match ヘッダーでオプティミスティック同時実行制御の書き込み操作のためです。</param>
        <summary>
            StreamingJobsUpdateHeaders クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ETag">
      <MemberSignature Language="C#" Value="public string ETag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ETag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJobsUpdateHeaders.ETag" />
      <MemberSignature Language="VB.NET" Value="Public Property ETag As String" />
      <MemberSignature Language="F#" Value="member this.ETag : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJobsUpdateHeaders.ETag" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="ETag")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはストリーミング ジョブの現在のエンティティ タグを設定します。 これは、不透明な文字列です。 要求間でリソースが変更されたかどうかを検出するために使用できます。 使用することできますも、If-match または [なし]-If-match ヘッダーでオプティミスティック同時実行制御の書き込み操作のためです。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>