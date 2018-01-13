<Type Name="PowerBIOutputDataSource" FullName="Microsoft.Azure.Management.StreamAnalytics.Models.PowerBIOutputDataSource">
  <TypeSignature Language="C#" Value="public class PowerBIOutputDataSource : Microsoft.Azure.Management.StreamAnalytics.Models.OutputDataSource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PowerBIOutputDataSource extends Microsoft.Azure.Management.StreamAnalytics.Models.OutputDataSource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StreamAnalytics.Models.PowerBIOutputDataSource" />
  <TypeSignature Language="VB.NET" Value="Public Class PowerBIOutputDataSource&#xA;Inherits OutputDataSource" />
  <TypeSignature Language="F#" Value="type PowerBIOutputDataSource = class&#xA;    inherit OutputDataSource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.StreamAnalytics.Models.OutputDataSource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject("PowerBI")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Power BI 出力のデータ ソースをについて説明します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PowerBIOutputDataSource ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.PowerBIOutputDataSource.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            PowerBIOutputDataSource クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PowerBIOutputDataSource (string refreshToken = null, string tokenUserPrincipalName = null, string tokenUserDisplayName = null, string dataset = null, string table = null, string groupId = null, string groupName = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string refreshToken, string tokenUserPrincipalName, string tokenUserDisplayName, string dataset, string table, string groupId, string groupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.PowerBIOutputDataSource.#ctor(System.String,System.String,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional refreshToken As String = null, Optional tokenUserPrincipalName As String = null, Optional tokenUserDisplayName As String = null, Optional dataset As String = null, Optional table As String = null, Optional groupId As String = null, Optional groupName As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StreamAnalytics.Models.PowerBIOutputDataSource : string * string * string * string * string * string * string -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.PowerBIOutputDataSource" Usage="new Microsoft.Azure.Management.StreamAnalytics.Models.PowerBIOutputDataSource (refreshToken, tokenUserPrincipalName, tokenUserDisplayName, dataset, table, groupId, groupName)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="refreshToken" Type="System.String" />
        <Parameter Name="tokenUserPrincipalName" Type="System.String" />
        <Parameter Name="tokenUserDisplayName" Type="System.String" />
        <Parameter Name="dataset" Type="System.String" />
        <Parameter Name="table" Type="System.String" />
        <Parameter Name="groupId" Type="System.String" />
        <Parameter Name="groupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="refreshToken">データ ソースに認証するために使用する有効なアクセス トークンの取得に使用できる更新トークンです。 有効な更新トークンは、現在、Azure ポータル経由で取得できのみです。 データ ソースと有効な更新トークンを使用してこのプロパティを更新する必要があるデータ ソースの認証に Azure ポータルに、継続を作成するときに、ダミーの文字列値をここに記述することをお勧めします。 PUT (CreateOrReplace) 要求に必要です。</param>
        <param name="tokenUserPrincipalName">ユーザー プリンシパル名 (UPN)、更新トークンを取得するために使用されたユーザーのです。 このプロパティを使用して、ヘルプのユーザーが更新トークンの取得に使用されたに注意してください。</param>
        <param name="tokenUserDisplayName">更新トークンを取得するために使用されたユーザーのユーザーの表示名。 このプロパティを使用して、ヘルプのユーザーが更新トークンの取得に使用されたに注意してください。</param>
        <param name="dataset">Power BI データセットの名前。 PUT (CreateOrReplace) 要求に必要です。</param>
        <param name="table">指定されたデータセットで Power BI テーブルの名前。 PUT (CreateOrReplace) 要求に必要です。</param>
        <param name="groupId">Power BI グループの ID。</param>
        <param name="groupName">Power BI グループの名前。 このプロパティを使用して、支援する特定の Power BI グループ id の使用に注意してください。</param>
        <summary>
            PowerBIOutputDataSource クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Dataset">
      <MemberSignature Language="C#" Value="public string Dataset { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Dataset" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.PowerBIOutputDataSource.Dataset" />
      <MemberSignature Language="VB.NET" Value="Public Property Dataset As String" />
      <MemberSignature Language="F#" Value="member this.Dataset : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.PowerBIOutputDataSource.Dataset" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.dataset")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または Power BI のデータセットの名前を設定します。 PUT (CreateOrReplace) 要求に必要です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GroupId">
      <MemberSignature Language="C#" Value="public string GroupId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string GroupId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.PowerBIOutputDataSource.GroupId" />
      <MemberSignature Language="VB.NET" Value="Public Property GroupId As String" />
      <MemberSignature Language="F#" Value="member this.GroupId : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.PowerBIOutputDataSource.GroupId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.groupId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または Power BI グループの ID を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GroupName">
      <MemberSignature Language="C#" Value="public string GroupName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string GroupName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.PowerBIOutputDataSource.GroupName" />
      <MemberSignature Language="VB.NET" Value="Public Property GroupName As String" />
      <MemberSignature Language="F#" Value="member this.GroupName : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.PowerBIOutputDataSource.GroupName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.groupName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または Power BI グループの名前を設定します。 このプロパティを使用して、支援する特定の Power BI グループ id の使用に注意してください。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RefreshToken">
      <MemberSignature Language="C#" Value="public string RefreshToken { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RefreshToken" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.PowerBIOutputDataSource.RefreshToken" />
      <MemberSignature Language="VB.NET" Value="Public Property RefreshToken As String" />
      <MemberSignature Language="F#" Value="member this.RefreshToken : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.PowerBIOutputDataSource.RefreshToken" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.refreshToken")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはデータ ソースに認証するために使用する有効なアクセス トークンの取得に使用できる更新トークンを設定します。 有効な更新トークンは、現在、Azure ポータル経由で取得できのみです。 データ ソースと有効な更新トークンを使用してこのプロパティを更新する必要があるデータ ソースの認証に Azure ポータルに、継続を作成するときに、ダミーの文字列値をここに記述することをお勧めします。 PUT (CreateOrReplace) 要求に必要です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Table">
      <MemberSignature Language="C#" Value="public string Table { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Table" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.PowerBIOutputDataSource.Table" />
      <MemberSignature Language="VB.NET" Value="Public Property Table As String" />
      <MemberSignature Language="F#" Value="member this.Table : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.PowerBIOutputDataSource.Table" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.table")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または指定されたデータセットで Power BI テーブルの名前を設定します。 PUT (CreateOrReplace) 要求に必要です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TokenUserDisplayName">
      <MemberSignature Language="C#" Value="public string TokenUserDisplayName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TokenUserDisplayName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.PowerBIOutputDataSource.TokenUserDisplayName" />
      <MemberSignature Language="VB.NET" Value="Public Property TokenUserDisplayName As String" />
      <MemberSignature Language="F#" Value="member this.TokenUserDisplayName : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.PowerBIOutputDataSource.TokenUserDisplayName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.tokenUserDisplayName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または更新トークンを取得するために使用されたユーザーのユーザーの表示名を設定します。 このプロパティを使用して、ヘルプのユーザーが更新トークンの取得に使用されたに注意してください。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TokenUserPrincipalName">
      <MemberSignature Language="C#" Value="public string TokenUserPrincipalName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TokenUserPrincipalName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.PowerBIOutputDataSource.TokenUserPrincipalName" />
      <MemberSignature Language="VB.NET" Value="Public Property TokenUserPrincipalName As String" />
      <MemberSignature Language="F#" Value="member this.TokenUserPrincipalName : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.PowerBIOutputDataSource.TokenUserPrincipalName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.tokenUserPrincipalName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または更新トークンを取得するために使用されたユーザーのユーザー プリンシパル名 (UPN) を設定します。 このプロパティを使用して、ヘルプのユーザーが更新トークンの取得に使用されたに注意してください。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>