<Type Name="RestoreRequest" FullName="Microsoft.Azure.Management.WebSites.Models.RestoreRequest">
  <TypeSignature Language="C#" Value="public class RestoreRequest : Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RestoreRequest extends Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.RestoreRequest" />
  <TypeSignature Language="VB.NET" Value="Public Class RestoreRequest&#xA;Inherits ProxyOnlyResource" />
  <TypeSignature Language="F#" Value="type RestoreRequest = class&#xA;    inherit ProxyOnlyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.WebSites.Models.Resource</BaseTypeName>
    <BaseTypeName FrameworkAlternate="azure-dotnet">Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            復元要求の説明です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RestoreRequest ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.RestoreRequest.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            RestoreRequest クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RestoreRequest (string id = null, string name = null, string kind = null, string type = null, string storageAccountUrl = null, string blobName = null, Nullable&lt;bool&gt; overwrite = null, string siteName = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.DatabaseBackupSetting&gt; databases = null, Nullable&lt;bool&gt; ignoreConflictingHostNames = null, Nullable&lt;bool&gt; ignoreDatabases = null, string appServicePlan = null, Nullable&lt;Microsoft.Azure.Management.WebSites.Models.BackupRestoreOperationType&gt; operationType = null, Nullable&lt;bool&gt; adjustConnectionStrings = null, string hostingEnvironment = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string kind, string type, string storageAccountUrl, string blobName, valuetype System.Nullable`1&lt;bool&gt; overwrite, string siteName, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.DatabaseBackupSetting&gt; databases, valuetype System.Nullable`1&lt;bool&gt; ignoreConflictingHostNames, valuetype System.Nullable`1&lt;bool&gt; ignoreDatabases, string appServicePlan, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.BackupRestoreOperationType&gt; operationType, valuetype System.Nullable`1&lt;bool&gt; adjustConnectionStrings, string hostingEnvironment) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.RestoreRequest.#ctor(System.String,System.String,System.String,System.String,System.String,System.String,System.Nullable{System.Boolean},System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.WebSites.Models.DatabaseBackupSetting},System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.String,System.Nullable{Microsoft.Azure.Management.WebSites.Models.BackupRestoreOperationType},System.Nullable{System.Boolean},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional kind As String = null, Optional type As String = null, Optional storageAccountUrl As String = null, Optional blobName As String = null, Optional overwrite As Nullable(Of Boolean) = null, Optional siteName As String = null, Optional databases As IList(Of DatabaseBackupSetting) = null, Optional ignoreConflictingHostNames As Nullable(Of Boolean) = null, Optional ignoreDatabases As Nullable(Of Boolean) = null, Optional appServicePlan As String = null, Optional operationType As Nullable(Of BackupRestoreOperationType) = null, Optional adjustConnectionStrings As Nullable(Of Boolean) = null, Optional hostingEnvironment As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.RestoreRequest : string * string * string * string * string * string * Nullable&lt;bool&gt; * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.DatabaseBackupSetting&gt; * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * string * Nullable&lt;Microsoft.Azure.Management.WebSites.Models.BackupRestoreOperationType&gt; * Nullable&lt;bool&gt; * string -&gt; Microsoft.Azure.Management.WebSites.Models.RestoreRequest" Usage="new Microsoft.Azure.Management.WebSites.Models.RestoreRequest (id, name, kind, type, storageAccountUrl, blobName, overwrite, siteName, databases, ignoreConflictingHostNames, ignoreDatabases, appServicePlan, operationType, adjustConnectionStrings, hostingEnvironment)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="kind" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="storageAccountUrl" Type="System.String" />
        <Parameter Name="blobName" Type="System.String" />
        <Parameter Name="overwrite" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="siteName" Type="System.String" />
        <Parameter Name="databases" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.DatabaseBackupSetting&gt;" />
        <Parameter Name="ignoreConflictingHostNames" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="ignoreDatabases" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="appServicePlan" Type="System.String" />
        <Parameter Name="operationType" Type="System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.BackupRestoreOperationType&gt;" />
        <Parameter Name="adjustConnectionStrings" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="hostingEnvironment" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id">リソース id です。</param>
        <param name="name">リソースの名前です。</param>
        <param name="kind">リソースの種類。</param>
        <param name="type">リソースの種類。</param>
        <param name="storageAccountUrl">コンテナーの SAS URL。</param>
        <param name="blobName">バックアップが格納されている blob の名前。</param>
        <param name="overwrite">&lt;コード&gt;true&lt;/code&gt; 、復元操作が対象とするアプリケーション; を上書きできる場合それ以外の場合、&lt;コード&gt;false&lt;/code&gt;です。 &lt;コード&gt;true&lt;/code&gt;を既存のアプリケーションを復元しようとしている場合に必要です。</param>
        <param name="siteName">アプリの名前です。</param>
        <param name="databases">復元するデータベースのコレクションです。 この一覧には、バックアップに含まれているデータベースの一覧を表示します。</param>
        <param name="ignoreConflictingHostNames">カスタム ドメインを使用してアプリを復元するときに、ロジックを変更します。 &lt;コード&gt;true&lt;/code&gt;カスタム ドメインを自動的に削除します。 場合&lt;コード&gt;false&lt;/code&gt;、復元しているが、操作中に競合のため失敗する可能性があります、アプリのオブジェクトにカスタム ドメインを追加します。</param>
        <param name="ignoreDatabases">データベースを無視し、サイトのコンテンツの復元のみ</param>
        <param name="appServicePlan">App service プランに復元されたサイトを所有するを指定します。</param>
        <param name="operationType">操作の種類。 使用可能な値が含まれます: 'Default'、' Clone'、'再配置'、'Snapshot'</param>
        <param name="adjustConnectionStrings">&lt;コード&gt;true&lt;/code&gt; SiteConfig.ConnectionStrings を新しいアプリ; に設定する必要がある場合それ以外の場合、&lt;コード&gt;false&lt;/code&gt;です。</param>
        <param name="hostingEnvironment">App Service 環境名、(場合にのみ、アプリの App Service 環境を復元) が必要な場合です。</param>
        <summary>
            RestoreRequest クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AdjustConnectionStrings">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; AdjustConnectionStrings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; AdjustConnectionStrings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.RestoreRequest.AdjustConnectionStrings" />
      <MemberSignature Language="VB.NET" Value="Public Property AdjustConnectionStrings As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.AdjustConnectionStrings : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.RestoreRequest.AdjustConnectionStrings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.adjustConnectionStrings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定&amp;lt; コード&amp;gt 以外の場合は true&amp;lt;/code&amp;gt; 場合は新しいアプリ; SiteConfig.ConnectionStrings を設定する必要がそれ以外の場合、 &amp;lt; コード&amp;gt; false&amp;lt;/code。&amp;gt;。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AppServicePlan">
      <MemberSignature Language="C#" Value="public string AppServicePlan { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AppServicePlan" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.RestoreRequest.AppServicePlan" />
      <MemberSignature Language="VB.NET" Value="Public Property AppServicePlan As String" />
      <MemberSignature Language="F#" Value="member this.AppServicePlan : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.RestoreRequest.AppServicePlan" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.appServicePlan")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定は、復元されたサイトを所有する app service プランを指定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BlobName">
      <MemberSignature Language="C#" Value="public string BlobName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string BlobName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.RestoreRequest.BlobName" />
      <MemberSignature Language="VB.NET" Value="Public Property BlobName As String" />
      <MemberSignature Language="F#" Value="member this.BlobName : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.RestoreRequest.BlobName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.blobName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはバックアップが格納されている blob の名前を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Databases">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.DatabaseBackupSetting&gt; Databases { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.DatabaseBackupSetting&gt; Databases" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.RestoreRequest.Databases" />
      <MemberSignature Language="VB.NET" Value="Public Property Databases As IList(Of DatabaseBackupSetting)" />
      <MemberSignature Language="F#" Value="member this.Databases : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.DatabaseBackupSetting&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.RestoreRequest.Databases" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.databases")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.DatabaseBackupSetting&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または復元するデータベースのコレクションを設定します。 この一覧には、バックアップに含まれているデータベースの一覧を表示します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HostingEnvironment">
      <MemberSignature Language="C#" Value="public string HostingEnvironment { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string HostingEnvironment" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.RestoreRequest.HostingEnvironment" />
      <MemberSignature Language="VB.NET" Value="Public Property HostingEnvironment As String" />
      <MemberSignature Language="F#" Value="member this.HostingEnvironment : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.RestoreRequest.HostingEnvironment" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.hostingEnvironment")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または (場合にのみ、アプリの App Service 環境を復元) が必要な場合に、app Service 環境名を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IgnoreConflictingHostNames">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IgnoreConflictingHostNames { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IgnoreConflictingHostNames" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.RestoreRequest.IgnoreConflictingHostNames" />
      <MemberSignature Language="VB.NET" Value="Public Property IgnoreConflictingHostNames As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IgnoreConflictingHostNames : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.RestoreRequest.IgnoreConflictingHostNames" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.ignoreConflictingHostNames")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはカスタム ドメインを使用してアプリを復元するときに、変更、ロジックを設定します。 &amp;lt; コード&amp;gt; true&amp;lt;/code&amp;gt; のカスタム ドメインを自動的に削除します。 場合&amp;lt; コード&amp;gt 以外の場合は false&amp;lt;/code&amp;gt;、復元しているが、操作中に競合のため失敗する可能性があります、アプリのオブジェクトにカスタム ドメインを追加します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IgnoreDatabases">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IgnoreDatabases { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IgnoreDatabases" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.RestoreRequest.IgnoreDatabases" />
      <MemberSignature Language="VB.NET" Value="Public Property IgnoreDatabases As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IgnoreDatabases : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.RestoreRequest.IgnoreDatabases" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.ignoreDatabases")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            データベースを無視し、サイトのコンテンツの復元のみを取得または設定
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OperationType">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.WebSites.Models.BackupRestoreOperationType&gt; OperationType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.BackupRestoreOperationType&gt; OperationType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.RestoreRequest.OperationType" />
      <MemberSignature Language="VB.NET" Value="Public Property OperationType As Nullable(Of BackupRestoreOperationType)" />
      <MemberSignature Language="F#" Value="member this.OperationType : Nullable&lt;Microsoft.Azure.Management.WebSites.Models.BackupRestoreOperationType&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.RestoreRequest.OperationType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.operationType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.BackupRestoreOperationType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または操作の種類を設定します。 使用可能な値が含まれます: 'Default'、' Clone'、'再配置'、'Snapshot'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Overwrite">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; Overwrite { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; Overwrite" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.RestoreRequest.Overwrite" />
      <MemberSignature Language="VB.NET" Value="Public Property Overwrite As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.Overwrite : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.RestoreRequest.Overwrite" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.overwrite")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定&amp;lt; コード&amp;gt 以外の場合は true&amp;lt;/code&amp;gt;、復元操作が対象とするアプリケーション; を上書きできる場合それ以外の場合、 &amp;lt; コード&amp;gt; false&amp;lt;/code。&amp;gt;。
            &amp;lt; コード&amp;gt 以外の場合は true。&amp;lt;/code&amp;gt; を既存のアプリケーションを復元しようとしている場合に必要です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SiteName">
      <MemberSignature Language="C#" Value="public string SiteName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SiteName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.RestoreRequest.SiteName" />
      <MemberSignature Language="VB.NET" Value="Public Property SiteName As String" />
      <MemberSignature Language="F#" Value="member this.SiteName : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.RestoreRequest.SiteName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.siteName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはアプリの名前を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageAccountUrl">
      <MemberSignature Language="C#" Value="public string StorageAccountUrl { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StorageAccountUrl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.RestoreRequest.StorageAccountUrl" />
      <MemberSignature Language="VB.NET" Value="Public Property StorageAccountUrl As String" />
      <MemberSignature Language="F#" Value="member this.StorageAccountUrl : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.RestoreRequest.StorageAccountUrl" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.storageAccountUrl")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはコンテナー SAS URL を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>