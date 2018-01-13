<Type Name="Permission" FullName="Microsoft.Azure.Documents.Permission">
  <TypeSignature Language="C#" Value="public class Permission : Microsoft.Azure.Documents.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Permission extends Microsoft.Azure.Documents.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.Permission" />
  <TypeSignature Language="VB.NET" Value="Public Class Permission&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type Permission = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
    <AssemblyVersion>1.6.0.0</AssemblyVersion>
    <AssemblyVersion>1.7.0.0</AssemblyVersion>
    <AssemblyVersion>1.7.1.0</AssemblyVersion>
  </AssemblyInfo>
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
    <AssemblyVersion>1.18.0.0</AssemblyVersion>
    <AssemblyVersion>1.19.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Documents.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            サービスでは Azure Cosmos DB、ドキュメントやコレクションなどの特定のリソースにアクセスするユーザーごとのアクセス許可を表します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Permission ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Permission.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PermissionMode">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Documents.PermissionMode PermissionMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Documents.PermissionMode PermissionMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Permission.PermissionMode" />
      <MemberSignature Language="VB.NET" Value="Public Property PermissionMode As PermissionMode" />
      <MemberSignature Language="F#" Value="member this.PermissionMode : Microsoft.Azure.Documents.PermissionMode with get, set" Usage="Microsoft.Azure.Documents.Permission.PermissionMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonConverter(typeof(Newtonsoft.Json.Converters.StringEnumConverter))</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="permissionMode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Documents.PermissionMode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または Azure Cosmos DB サービスのアクセス許可モードを設定します。
            </summary>
        <value>
            <see cref="P:Microsoft.Azure.Documents.Permission.PermissionMode" />モード: すべての読み取りまたはします。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceLink">
      <MemberSignature Language="C#" Value="public string ResourceLink { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResourceLink" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Permission.ResourceLink" />
      <MemberSignature Language="VB.NET" Value="Public Property ResourceLink As String" />
      <MemberSignature Language="F#" Value="member this.ResourceLink : string with get, set" Usage="Microsoft.Azure.Documents.Permission.ResourceLink" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="resource")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary> 
            取得または Azure Cosmos DB サービスの権限が適用されるリソースの自己リンクを設定します。
            </summary>
        <value>
            自己リンク、リソース、アクセス許可が適用されます。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourcePartitionKey">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Documents.PartitionKey ResourcePartitionKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Documents.PartitionKey ResourcePartitionKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Permission.ResourcePartitionKey" />
      <MemberSignature Language="VB.NET" Value="Public Property ResourcePartitionKey As PartitionKey" />
      <MemberSignature Language="F#" Value="member this.ResourcePartitionKey : Microsoft.Azure.Documents.PartitionKey with get, set" Usage="Microsoft.Azure.Documents.Permission.ResourcePartitionKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="resourcePartitionKey")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Documents.PartitionKey</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または Azure Cosmos DB サービスのアクセス許可の省略可能なパーティション キー値を設定します。
            アクセス許可は、2 つの条件が満たされたときに、リソースに適用されます。
                  1. <see cref="P:Microsoft.Azure.Documents.Permission.ResourceLink" />リソースのリンクのプレフィックスです。
                        たとえば「/db mydatabase/colls/mycollection」適用「/db mydatabase/colls/mycollection」に、「/db/mydatabase/colls/mycollection/docs/mydocument」
                  2. <see cref="P:Microsoft.Azure.Documents.Permission.ResourcePartitionKey" />リソースのパーティション キーのスーパー セットです。
                        たとえば、存在しないか空のパーティション キーはのスーパー セットのすべてのパーティション キーです。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Token">
      <MemberSignature Language="C#" Value="public string Token { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Token" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Permission.Token" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Token As String" />
      <MemberSignature Language="F#" Value="member this.Token : string" Usage="Microsoft.Azure.Documents.Permission.Token" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="_token")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Azure Cosmos DB サービスから定義されたアクセス許可を付与するアクセス トークンを取得します。
            </summary>
        <value>
            定義されたアクセス許可を付与するアクセス トークンです。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>