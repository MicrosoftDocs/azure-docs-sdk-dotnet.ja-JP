<Type Name="DataLakeAnalyticsAccountBasic" FullName="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountBasic">
  <TypeSignature Language="C#" Value="public class DataLakeAnalyticsAccountBasic : Microsoft.Azure.Management.DataLake.Analytics.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DataLakeAnalyticsAccountBasic extends Microsoft.Azure.Management.DataLake.Analytics.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountBasic" />
  <TypeSignature Language="VB.NET" Value="Public Class DataLakeAnalyticsAccountBasic&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type DataLakeAnalyticsAccountBasic = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataLake.Analytics.Models.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Data Lake Analytics アカウント オブジェクト、名前付きの Data Lake Analytics アカウントに関連付けられているすべての情報を格納します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataLakeAnalyticsAccountBasic ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountBasic.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            DataLakeAnalyticsAccountBasic クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataLakeAnalyticsAccountBasic (string location, string id = null, string name = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountStatus&gt; provisioningState = null, Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountState&gt; state = null, Nullable&lt;DateTime&gt; creationTime = null, Nullable&lt;DateTime&gt; lastModifiedTime = null, string endpoint = null, Nullable&lt;Guid&gt; accountId = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, string id, string name, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountStatus&gt; provisioningState, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountState&gt; state, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; creationTime, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; lastModifiedTime, string endpoint, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; accountId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountBasic.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.Nullable{Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountStatus},System.Nullable{Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountState},System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.String,System.Nullable{System.Guid})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (location As String, Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional tags As IDictionary(Of String, String) = null, Optional provisioningState As Nullable(Of DataLakeAnalyticsAccountStatus) = null, Optional state As Nullable(Of DataLakeAnalyticsAccountState) = null, Optional creationTime As Nullable(Of DateTime) = null, Optional lastModifiedTime As Nullable(Of DateTime) = null, Optional endpoint As String = null, Optional accountId As Nullable(Of Guid) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountBasic : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountStatus&gt; * Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountState&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * string * Nullable&lt;Guid&gt; -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountBasic" Usage="new Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountBasic (location, id, name, type, tags, provisioningState, state, creationTime, lastModifiedTime, endpoint, accountId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="provisioningState" Type="System.Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountStatus&gt;" />
        <Parameter Name="state" Type="System.Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountState&gt;" />
        <Parameter Name="creationTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="lastModifiedTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="endpoint" Type="System.String" />
        <Parameter Name="accountId" Type="System.Nullable&lt;System.Guid&gt;" />
      </Parameters>
      <Docs>
        <param name="location">リソースの場所</param>
        <param name="id">リソース Id</param>
        <param name="name">リソース名</param>
        <param name="type">リソースの種類</param>
        <param name="tags">リソース タグ</param>
        <param name="provisioningState">Data Lake Analytics アカウントのプロビジョニング状態。 使用可能な値が含まれます: '失敗'、'作成中'、'実行'、'成功'、'パッチ'、'一時停止中'、'再開'、'削除'、'Deleted'</param>
        <param name="state">Data Lake Analytics アカウントの状態。
            使用可能な値が含まれます: 'Active'、'中断'</param>
        <param name="creationTime">アカウントの作成時。</param>
        <param name="lastModifiedTime">アカウントには、最終更新時刻を設定します。</param>
        <param name="endpoint">このアカウントの完全な CName エンドポイント。</param>
        <param name="accountId">この Data Lake Analytics アカウントに関連付けられている一意の識別子。</param>
        <summary>
            DataLakeAnalyticsAccountBasic クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AccountId">
      <MemberSignature Language="C#" Value="public Nullable&lt;Guid&gt; AccountId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.Guid&gt; AccountId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountBasic.AccountId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AccountId As Nullable(Of Guid)" />
      <MemberSignature Language="F#" Value="member this.AccountId : Nullable&lt;Guid&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountBasic.AccountId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.accountId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Guid&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            この Data Lake Analytics アカウントに関連付けられている一意の識別子を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreationTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; CreationTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; CreationTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountBasic.CreationTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CreationTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.CreationTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountBasic.CreationTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.creationTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            アカウントの作成時間を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Endpoint">
      <MemberSignature Language="C#" Value="public string Endpoint { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Endpoint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountBasic.Endpoint" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Endpoint As String" />
      <MemberSignature Language="F#" Value="member this.Endpoint : string" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountBasic.Endpoint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.endpoint")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            このアカウントに、完全な CName エンドポイントを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastModifiedTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; LastModifiedTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; LastModifiedTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountBasic.LastModifiedTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastModifiedTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.LastModifiedTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountBasic.LastModifiedTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.lastModifiedTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            アカウントの最終更新時刻を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountStatus&gt; ProvisioningState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountStatus&gt; ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountBasic.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningState As Nullable(Of DataLakeAnalyticsAccountStatus)" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountStatus&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountBasic.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.provisioningState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountStatus&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Data Lake Analytics アカウントのプロビジョニング状態を取得します。
            使用可能な値が含まれます: '失敗'、'作成中'、'実行'、'成功'、'パッチ'、'一時停止中'、'再開'、'削除'、'Deleted'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="State">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountState&gt; State { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountState&gt; State" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountBasic.State" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property State As Nullable(Of DataLakeAnalyticsAccountState)" />
      <MemberSignature Language="F#" Value="member this.State : Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountState&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountBasic.State" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.state")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Data Lake Analytics アカウントの状態を取得します。 使用可能な値が含まれます: 'Active'、'中断'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountBasic.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="dataLakeAnalyticsAccountBasic.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
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