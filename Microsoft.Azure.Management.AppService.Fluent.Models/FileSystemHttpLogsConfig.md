<Type Name="FileSystemHttpLogsConfig" FullName="Microsoft.Azure.Management.AppService.Fluent.Models.FileSystemHttpLogsConfig">
  <TypeSignature Language="C#" Value="public class FileSystemHttpLogsConfig" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit FileSystemHttpLogsConfig extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.Models.FileSystemHttpLogsConfig" />
  <TypeSignature Language="VB.NET" Value="Public Class FileSystemHttpLogsConfig" />
  <TypeSignature Language="F#" Value="type FileSystemHttpLogsConfig = class" />
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
            Http ログ ファイルのシステム構成にします。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FileSystemHttpLogsConfig ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.FileSystemHttpLogsConfig.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            FileSystemHttpLogsConfig クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FileSystemHttpLogsConfig (Nullable&lt;int&gt; retentionInMb = null, Nullable&lt;int&gt; retentionInDays = null, Nullable&lt;bool&gt; enabled = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;int32&gt; retentionInMb, valuetype System.Nullable`1&lt;int32&gt; retentionInDays, valuetype System.Nullable`1&lt;bool&gt; enabled) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.FileSystemHttpLogsConfig.#ctor(System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional retentionInMb As Nullable(Of Integer) = null, Optional retentionInDays As Nullable(Of Integer) = null, Optional enabled As Nullable(Of Boolean) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.AppService.Fluent.Models.FileSystemHttpLogsConfig : Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Management.AppService.Fluent.Models.FileSystemHttpLogsConfig" Usage="new Microsoft.Azure.Management.AppService.Fluent.Models.FileSystemHttpLogsConfig (retentionInMb, retentionInDays, enabled)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="retentionInMb" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="retentionInDays" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="enabled" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="retentionInMb">Http ログ ファイルが使用できるメガバイト単位で最大サイズ。
            古いに達したときに、新規の領域をログ ファイルが削除されません。
            25 ~ 100 の範囲値の範囲はします。</param>
        <param name="retentionInDays">保有期間日数。
            次の日数より古いファイルを削除します。
            0 または下には、保有期間、なしです。</param>
        <param name="enabled">有効になります。</param>
        <summary>
            FileSystemHttpLogsConfig クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Enabled">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; Enabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; Enabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.FileSystemHttpLogsConfig.Enabled" />
      <MemberSignature Language="VB.NET" Value="Public Property Enabled As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.Enabled : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.FileSystemHttpLogsConfig.Enabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="enabled")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定が有効にします。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetentionInDays">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; RetentionInDays { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; RetentionInDays" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.FileSystemHttpLogsConfig.RetentionInDays" />
      <MemberSignature Language="VB.NET" Value="Public Property RetentionInDays As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.RetentionInDays : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.FileSystemHttpLogsConfig.RetentionInDays" />
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
            次の日数より古いファイルを削除します。
            0 または下には、保有期間、なしです。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetentionInMb">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; RetentionInMb { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; RetentionInMb" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.FileSystemHttpLogsConfig.RetentionInMb" />
      <MemberSignature Language="VB.NET" Value="Public Property RetentionInMb As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.RetentionInMb : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.FileSystemHttpLogsConfig.RetentionInMb" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="retentionInMb")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または http ログ ファイルが使用できるメガバイト単位で最大サイズを設定します。
            古いに達したときに、新規の領域をログ ファイルが削除されません。
            25 ~ 100 の範囲値の範囲はします。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.FileSystemHttpLogsConfig.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="fileSystemHttpLogsConfig.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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