<Type Name="JsonSerializer" FullName="Microsoft.ApplicationInsights.Extensibility.Implementation.JsonSerializer">
  <TypeSignature Language="C#" Value="public static class JsonSerializer" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit JsonSerializer extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ApplicationInsights.Extensibility.Implementation.JsonSerializer" />
  <TypeSignature Language="VB.NET" Value="Public Class JsonSerializer" />
  <TypeSignature Language="F#" Value="type JsonSerializer = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
    <AssemblyVersion>2.3.0.0</AssemblyVersion>
    <AssemblyVersion>2.5.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.ComponentModel.EditorBrowsable(System.ComponentModel.EditorBrowsableState.Never)</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            シリアル化し、JSON 文字列にテレメトリ項目を圧縮します。 圧縮は行われます GZIP を使用してその API はサポートされているために、Windows Phone 8 の圧縮は無効になります。 
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CompressionType">
      <MemberSignature Language="C#" Value="public static string CompressionType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property string CompressionType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.Extensibility.Implementation.JsonSerializer.CompressionType" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property CompressionType As String" />
      <MemberSignature Language="F#" Value="member this.CompressionType : string" Usage="Microsoft.ApplicationInsights.Extensibility.Implementation.JsonSerializer.CompressionType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            シリアライザーで使用される圧縮の種類を取得します。 
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContentType">
      <MemberSignature Language="C#" Value="public static string ContentType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property string ContentType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.Extensibility.Implementation.JsonSerializer.ContentType" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property ContentType As String" />
      <MemberSignature Language="F#" Value="member this.ContentType : string" Usage="Microsoft.ApplicationInsights.Extensibility.Implementation.JsonSerializer.ContentType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            シリアライザーで使用されるコンテンツの種類を取得します。 
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConvertToByteArray">
      <MemberSignature Language="C#" Value="public static byte[] ConvertToByteArray (string telemetryItems, bool compress = true);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig unsigned int8[] ConvertToByteArray(string telemetryItems, bool compress) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.Extensibility.Implementation.JsonSerializer.ConvertToByteArray(System.String,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function ConvertToByteArray (telemetryItems As String, Optional compress As Boolean = true) As Byte()" />
      <MemberSignature Language="F#" Value="static member ConvertToByteArray : string * bool -&gt; byte[]" Usage="Microsoft.ApplicationInsights.Extensibility.Implementation.JsonSerializer.ConvertToByteArray (telemetryItems, compress)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Usage", "CA2202:Do not dispose objects multiple times", Justification="Disposing a MemoryStream multiple times is harmless.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Byte[]</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="telemetryItems" Type="System.String" />
        <Parameter Name="compress" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="telemetryItems">製品利用統計情報項目をシリアル化されます。</param>
        <param name="compress">シリアル化はまた、圧縮を実行します。</param>
        <summary>
            変換は、バイト配列へのテレメトリ項目をシリアル化されます。
            </summary>
        <returns>圧縮およびシリアル化されたテレメトリ項目。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Deserialize">
      <MemberSignature Language="C#" Value="public static string Deserialize (byte[] telemetryItemsData, bool compress = true);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string Deserialize(unsigned int8[] telemetryItemsData, bool compress) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.Extensibility.Implementation.JsonSerializer.Deserialize(System.Byte[],System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Deserialize (telemetryItemsData As Byte(), Optional compress As Boolean = true) As String" />
      <MemberSignature Language="F#" Value="static member Deserialize : byte[] * bool -&gt; string" Usage="Microsoft.ApplicationInsights.Extensibility.Implementation.JsonSerializer.Deserialize (telemetryItemsData, compress)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="telemetryItemsData" Type="System.Byte[]" />
        <Parameter Name="compress" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="telemetryItemsData">製品利用統計情報項目をシリアル化されます。</param>
        <param name="compress">逆シリアル化はまた、圧縮解除を実行します。</param>
        <summary>
            逆シリアル化し、JSON 文字列を製品利用統計情報項目を解凍します。
            </summary>
        <returns>製品利用統計情報項目を文字列としてシリアル化します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Serialize">
      <MemberSignature Language="C#" Value="public static byte[] Serialize (System.Collections.Generic.IEnumerable&lt;Microsoft.ApplicationInsights.Channel.ITelemetry&gt; telemetryItems, bool compress = true);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig unsigned int8[] Serialize(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ApplicationInsights.Channel.ITelemetry&gt; telemetryItems, bool compress) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.Extensibility.Implementation.JsonSerializer.Serialize(System.Collections.Generic.IEnumerable{Microsoft.ApplicationInsights.Channel.ITelemetry},System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Serialize (telemetryItems As IEnumerable(Of ITelemetry), Optional compress As Boolean = true) As Byte()" />
      <MemberSignature Language="F#" Value="static member Serialize : seq&lt;Microsoft.ApplicationInsights.Channel.ITelemetry&gt; * bool -&gt; byte[]" Usage="Microsoft.ApplicationInsights.Extensibility.Implementation.JsonSerializer.Serialize (telemetryItems, compress)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Usage", "CA2202:Do not dispose objects multiple times", Justification="Disposing a MemoryStream multiple times is harmless.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Byte[]</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="telemetryItems" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.ApplicationInsights.Channel.ITelemetry&gt;" />
        <Parameter Name="compress" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="telemetryItems">シリアル化する項目を製品利用統計情報の一覧。</param>
        <param name="compress">シリアル化はまた、圧縮を実行します。</param>
        <summary>
            シリアル化し、JSON 文字列にテレメトリ項目を圧縮します。 各 JSON オブジェクトは、改行で区切られます。 
            </summary>
        <returns>圧縮およびシリアル化されたテレメトリ項目。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>