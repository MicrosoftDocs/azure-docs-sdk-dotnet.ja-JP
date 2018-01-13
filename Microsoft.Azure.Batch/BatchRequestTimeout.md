<Type Name="BatchRequestTimeout" FullName="Microsoft.Azure.Batch.BatchRequestTimeout">
  <TypeSignature Language="C#" Value="public class BatchRequestTimeout : Microsoft.Azure.Batch.Protocol.RequestInterceptor" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BatchRequestTimeout extends Microsoft.Azure.Batch.Protocol.RequestInterceptor" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.BatchRequestTimeout" />
  <TypeSignature Language="VB.NET" Value="Public Class BatchRequestTimeout&#xA;Inherits RequestInterceptor" />
  <TypeSignature Language="F#" Value="type BatchRequestTimeout = class&#xA;    inherit RequestInterceptor" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Batch.Protocol.RequestInterceptor</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            簡単にアクセスを提供するクラス、<see cref="P:Microsoft.Azure.Batch.Protocol.IBatchRequest.Timeout" />プロパティおよび<see cref="P:Microsoft.Azure.Batch.Protocol.Models.ITimeoutOptions.Timeout" />プロパティです。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BatchRequestTimeout (Nullable&lt;TimeSpan&gt; serverTimeout = null, Nullable&lt;TimeSpan&gt; clientTimeout = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; serverTimeout, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; clientTimeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.BatchRequestTimeout.#ctor(System.Nullable{System.TimeSpan},System.Nullable{System.TimeSpan})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional serverTimeout As Nullable(Of TimeSpan) = null, Optional clientTimeout As Nullable(Of TimeSpan) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.BatchRequestTimeout : Nullable&lt;TimeSpan&gt; * Nullable&lt;TimeSpan&gt; -&gt; Microsoft.Azure.Batch.BatchRequestTimeout" Usage="new Microsoft.Azure.Batch.BatchRequestTimeout (serverTimeout, clientTimeout)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serverTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="clientTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
      </Parameters>
      <Docs>
        <param name="serverTimeout">各要求に適用されるサーバーのタイムアウト。</param>
        <param name="clientTimeout">各要求に適用されるクライアントのタイムアウト。</param>
        <summary>
            <see cref="T:Microsoft.Azure.Batch.BatchRequestTimeout" /> クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientTimeout">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; ClientTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; ClientTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.BatchRequestTimeout.ClientTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property ClientTimeout As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.ClientTimeout : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.Azure.Batch.BatchRequestTimeout.ClientTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはバッチ サービスに発行される各要求に適用されるクライアントのタイムアウトを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServerTimeout">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; ServerTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; ServerTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.BatchRequestTimeout.ServerTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property ServerTimeout As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.ServerTimeout : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.Azure.Batch.BatchRequestTimeout.ServerTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはバッチ サービスに発行される各要求に適用されるサーバーのタイムアウトを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>