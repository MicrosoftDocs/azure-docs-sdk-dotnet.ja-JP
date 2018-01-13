<Type Name="AzureBlobStorageApplicationLogsConfig" FullName="Microsoft.Azure.Management.AppService.Fluent.Models.AzureBlobStorageApplicationLogsConfig">
  <TypeSignature Language="C#" Value="public class AzureBlobStorageApplicationLogsConfig" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AzureBlobStorageApplicationLogsConfig extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.Models.AzureBlobStorageApplicationLogsConfig" />
  <TypeSignature Language="VB.NET" Value="Public Class AzureBlobStorageApplicationLogsConfig" />
  <TypeSignature Language="F#" Value="type AzureBlobStorageApplicationLogsConfig = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            アプリケーションでは、azure blob ストレージの構成を記録します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureBlobStorageApplicationLogsConfig ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.AzureBlobStorageApplicationLogsConfig.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            AzureBlobStorageApplicationLogsConfig クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureBlobStorageApplicationLogsConfig (Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.LogLevel&gt; level = null, string sasUrl = null, Nullable&lt;int&gt; retentionInDays = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.AppService.Fluent.Models.LogLevel&gt; level, string sasUrl, valuetype System.Nullable`1&lt;int32&gt; retentionInDays) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.AzureBlobStorageApplicationLogsConfig.#ctor(System.Nullable{Microsoft.Azure.Management.AppService.Fluent.Models.LogLevel},System.String,System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional level As Nullable(Of LogLevel) = null, Optional sasUrl As String = null, Optional retentionInDays As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.AppService.Fluent.Models.AzureBlobStorageApplicationLogsConfig : Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.LogLevel&gt; * string * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Management.AppService.Fluent.Models.AzureBlobStorageApplicationLogsConfig" Usage="new Microsoft.Azure.Management.AppService.Fluent.Models.AzureBlobStorageApplicationLogsConfig (level, sasUrl, retentionInDays)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="level" Type="System.Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.LogLevel&gt;" />
        <Parameter Name="sasUrl" Type="System.String" />
        <Parameter Name="retentionInDays" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="level">ログ レベル。 使用可能な値が含まれます: 'Off'、'詳細'、'情報'、'警告'、'Error'</param>
        <param name="sasUrl">読み取り/書き込み/リスト/削除アクセス許可を持つ azure blob コンテナーの SAS url。</param>
        <param name="retentionInDays">保有期間日数。
            日数より古い blob を削除します。
            0 または下には、保有期間、なしです。</param>
        <summary>
            AzureBlobStorageApplicationLogsConfig クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Level">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.LogLevel&gt; Level { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.AppService.Fluent.Models.LogLevel&gt; Level" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.AzureBlobStorageApplicationLogsConfig.Level" />
      <MemberSignature Language="VB.NET" Value="Public Property Level As Nullable(Of LogLevel)" />
      <MemberSignature Language="F#" Value="member this.Level : Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.LogLevel&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.AzureBlobStorageApplicationLogsConfig.Level" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="level")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.LogLevel&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはログ レベルを設定します。 使用可能な値が含まれます: 'Off'、'詳細'、'情報'、'警告'、'Error'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetentionInDays">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; RetentionInDays { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; RetentionInDays" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.AzureBlobStorageApplicationLogsConfig.RetentionInDays" />
      <MemberSignature Language="VB.NET" Value="Public Property RetentionInDays As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.RetentionInDays : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.AzureBlobStorageApplicationLogsConfig.RetentionInDays" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="retentionInDays")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または保有期間を日に設定します。
            日数より古い blob を削除します。
            0 または下には、保有期間、なしです。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SasUrl">
      <MemberSignature Language="C#" Value="public string SasUrl { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SasUrl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.AzureBlobStorageApplicationLogsConfig.SasUrl" />
      <MemberSignature Language="VB.NET" Value="Public Property SasUrl As String" />
      <MemberSignature Language="F#" Value="member this.SasUrl : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.AzureBlobStorageApplicationLogsConfig.SasUrl" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sasUrl")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または読み取り/書き込み/リスト/削除アクセス許可を持つ azure blob コンテナーに SAS url を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>