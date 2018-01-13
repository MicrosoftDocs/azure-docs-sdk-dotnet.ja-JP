<Type Name="ImportRequest" FullName="Microsoft.Azure.Management.Sql.Models.ImportRequest">
  <TypeSignature Language="C#" Value="public class ImportRequest : Microsoft.Azure.Management.Sql.Models.ExportRequest" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ImportRequest extends Microsoft.Azure.Management.Sql.Models.ExportRequest" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Models.ImportRequest" />
  <TypeSignature Language="VB.NET" Value="Public Class ImportRequest&#xA;Inherits ExportRequest" />
  <TypeSignature Language="F#" Value="type ImportRequest = class&#xA;    inherit ExportRequest" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Sql.Models.ExportRequest</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            データベースのパラメーターをインポートします。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ImportRequest ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.ImportRequest.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            ImportRequest クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ImportRequest (Microsoft.Azure.Management.Sql.Models.StorageKeyType storageKeyType, string storageKey, string storageUri, string administratorLogin, string administratorLoginPassword, string databaseName, string edition, string serviceObjectiveName, string maxSizeBytes, Nullable&lt;Microsoft.Azure.Management.Sql.Models.AuthenticationType&gt; authenticationType = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.Azure.Management.Sql.Models.StorageKeyType storageKeyType, string storageKey, string storageUri, string administratorLogin, string administratorLoginPassword, string databaseName, string edition, string serviceObjectiveName, string maxSizeBytes, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Sql.Models.AuthenticationType&gt; authenticationType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.ImportRequest.#ctor(Microsoft.Azure.Management.Sql.Models.StorageKeyType,System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.Nullable{Microsoft.Azure.Management.Sql.Models.AuthenticationType})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.Models.ImportRequest : Microsoft.Azure.Management.Sql.Models.StorageKeyType * string * string * string * string * string * string * string * string * Nullable&lt;Microsoft.Azure.Management.Sql.Models.AuthenticationType&gt; -&gt; Microsoft.Azure.Management.Sql.Models.ImportRequest" Usage="new Microsoft.Azure.Management.Sql.Models.ImportRequest (storageKeyType, storageKey, storageUri, administratorLogin, administratorLoginPassword, databaseName, edition, serviceObjectiveName, maxSizeBytes, authenticationType)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="storageKeyType" Type="Microsoft.Azure.Management.Sql.Models.StorageKeyType" />
        <Parameter Name="storageKey" Type="System.String" />
        <Parameter Name="storageUri" Type="System.String" />
        <Parameter Name="administratorLogin" Type="System.String" />
        <Parameter Name="administratorLoginPassword" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="edition" Type="System.String" />
        <Parameter Name="serviceObjectiveName" Type="System.String" />
        <Parameter Name="maxSizeBytes" Type="System.String" />
        <Parameter Name="authenticationType" Type="System.Nullable&lt;Microsoft.Azure.Management.Sql.Models.AuthenticationType&gt;" />
      </Parameters>
      <Docs>
        <param name="storageKeyType">使用する記憶域のキーの型。
            使用可能な値が含まれます: 'StorageAccessKey'、'SharedAccessKey'</param>
        <param name="storageKey">使用する記憶域のキー。  記憶域のキーの種類が SharedAccessKey の場合は、前に必ずと、"?."</param>
        <param name="storageUri">使用する記憶域の uri。</param>
        <param name="administratorLogin">SQL 管理者の名前。</param>
        <param name="administratorLoginPassword">SQL 管理者のパスワードです。</param>
        <param name="databaseName">インポートするには、データベースの名前。</param>
        <param name="edition">作成するデータベースのエディションです。
            使用可能な値が含まれます: 'Web'、'ビジネス'、'Basic'、'Standard'、'Premium'、'無料'、'拡大'、'データ ウェアハウス'、'System'、'システム 2'</param>
        <param name="serviceObjectiveName">データベースに割り当てるサービス目標の名前。 使用可能な値が含まれます: 'Basic'、'S0'、'S1'、'S2'、'S3'、'P1'、'P2'、'P3'、'P4'、'P6'、'P11'、'P15'、'System'、'システム 2'、'ElasticPool'</param>
        <param name="maxSizeBytes">新しくインポートしたデータベースの最大サイズ。</param>
        <param name="authenticationType">認証の種類。 使用可能な値が含まれます 'SQL'、'ADPassword'。</param>
        <summary>
            ImportRequest クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DatabaseName">
      <MemberSignature Language="C#" Value="public string DatabaseName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DatabaseName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ImportRequest.DatabaseName" />
      <MemberSignature Language="VB.NET" Value="Public Property DatabaseName As String" />
      <MemberSignature Language="F#" Value="member this.DatabaseName : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.ImportRequest.DatabaseName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="databaseName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはインポートするには、データベースの名前を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Edition">
      <MemberSignature Language="C#" Value="public string Edition { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Edition" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ImportRequest.Edition" />
      <MemberSignature Language="VB.NET" Value="Public Property Edition As String" />
      <MemberSignature Language="F#" Value="member this.Edition : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.ImportRequest.Edition" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="edition")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または作成するデータベースのエディションを設定します。 使用可能な値が含まれます: 'Web'、'ビジネス'、'Basic'、'Standard'、'Premium'、'無料'、'拡大'、'データ ウェアハウス'、'System'、'システム 2'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxSizeBytes">
      <MemberSignature Language="C#" Value="public string MaxSizeBytes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MaxSizeBytes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ImportRequest.MaxSizeBytes" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxSizeBytes As String" />
      <MemberSignature Language="F#" Value="member this.MaxSizeBytes : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.ImportRequest.MaxSizeBytes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="maxSizeBytes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または新しくインポートしたデータベースの最大サイズを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceObjectiveName">
      <MemberSignature Language="C#" Value="public string ServiceObjectiveName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceObjectiveName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ImportRequest.ServiceObjectiveName" />
      <MemberSignature Language="VB.NET" Value="Public Property ServiceObjectiveName As String" />
      <MemberSignature Language="F#" Value="member this.ServiceObjectiveName : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.ImportRequest.ServiceObjectiveName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="serviceObjectiveName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはデータベースに割り当てるサービス目標の名前を設定します。 使用可能な値が含まれます: 'Basic'、'S0'、'S1'、'S2'、'S3'、'P1'、'P2'、'P3'、'P4'、'P6'、'P11'、'P15'、'System'、'システム 2'、'ElasticPool'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.ImportRequest.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="importRequest.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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