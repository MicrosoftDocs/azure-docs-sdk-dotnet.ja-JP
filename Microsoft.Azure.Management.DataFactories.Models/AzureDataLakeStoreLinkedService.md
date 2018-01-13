<Type Name="AzureDataLakeStoreLinkedService" FullName="Microsoft.Azure.Management.DataFactories.Models.AzureDataLakeStoreLinkedService">
  <TypeSignature Language="C#" Value="public class AzureDataLakeStoreLinkedService : Microsoft.Azure.Management.DataFactories.Models.LinkedServiceTypeProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AzureDataLakeStoreLinkedService extends Microsoft.Azure.Management.DataFactories.Models.LinkedServiceTypeProperties" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.Models.AzureDataLakeStoreLinkedService" />
  <TypeSignature Language="VB.NET" Value="Public Class AzureDataLakeStoreLinkedService&#xA;Inherits LinkedServiceTypeProperties" />
  <TypeSignature Language="F#" Value="type AzureDataLakeStoreLinkedService = class&#xA;    inherit LinkedServiceTypeProperties" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataFactories.Models.LinkedServiceTypeProperties</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Azure.Management.DataFactories.Models.AdfTypeName("AzureDataLakeStore")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Azure Data Lake Store のリンクされたサービス。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureDataLakeStoreLinkedService ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Models.AzureDataLakeStoreLinkedService.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <see cref="T:Microsoft.Azure.Management.DataFactories.Models.AzureDataLakeStoreLinkedService" /> クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureDataLakeStoreLinkedService (string dataLakeStoreUri);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string dataLakeStoreUri) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Models.AzureDataLakeStoreLinkedService.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (dataLakeStoreUri As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactories.Models.AzureDataLakeStoreLinkedService : string -&gt; Microsoft.Azure.Management.DataFactories.Models.AzureDataLakeStoreLinkedService" Usage="new Microsoft.Azure.Management.DataFactories.Models.AzureDataLakeStoreLinkedService dataLakeStoreUri" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="dataLakeStoreUri" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="dataLakeStoreUri">To be added.</param>
        <summary>
            新しいインスタンスを初期化、<see cref="T:Microsoft.Azure.Management.DataFactories.Models.AzureDataLakeStoreLinkedService" />必須の引数を持つクラス。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AccountName">
      <MemberSignature Language="C#" Value="public string AccountName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AccountName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.AzureDataLakeStoreLinkedService.AccountName" />
      <MemberSignature Language="VB.NET" Value="Public Property AccountName As String" />
      <MemberSignature Language="F#" Value="member this.AccountName : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.AzureDataLakeStoreLinkedService.AccountName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            省略可能。 Data Lake Store アカウントの名前です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Authorization">
      <MemberSignature Language="C#" Value="public string Authorization { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Authorization" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.AzureDataLakeStoreLinkedService.Authorization" />
      <MemberSignature Language="VB.NET" Value="Public Property Authorization As String" />
      <MemberSignature Language="F#" Value="member this.Authorization : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.AzureDataLakeStoreLinkedService.Authorization" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            あなたに代わってリソースにアクセスする ADF で使用する OAuth 承認します。 各認証には一意を一度だけ使用することがあります。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataLakeStoreUri">
      <MemberSignature Language="C#" Value="public string DataLakeStoreUri { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DataLakeStoreUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.AzureDataLakeStoreLinkedService.DataLakeStoreUri" />
      <MemberSignature Language="VB.NET" Value="Public Property DataLakeStoreUri As String" />
      <MemberSignature Language="F#" Value="member this.DataLakeStoreUri : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.AzureDataLakeStoreLinkedService.DataLakeStoreUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Management.DataFactories.Models.AdfRequired</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            必須。 Data Lake Store サービス URI です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceGroupName">
      <MemberSignature Language="C#" Value="public string ResourceGroupName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResourceGroupName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.AzureDataLakeStoreLinkedService.ResourceGroupName" />
      <MemberSignature Language="VB.NET" Value="Public Property ResourceGroupName As String" />
      <MemberSignature Language="F#" Value="member this.ResourceGroupName : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.AzureDataLakeStoreLinkedService.ResourceGroupName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            省略可能。 Data Lake Store アカウント リソース グループ名 (Data Factory アカウントとは異なる) 場合。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServicePrincipalId">
      <MemberSignature Language="C#" Value="public string ServicePrincipalId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServicePrincipalId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.AzureDataLakeStoreLinkedService.ServicePrincipalId" />
      <MemberSignature Language="VB.NET" Value="Public Property ServicePrincipalId As String" />
      <MemberSignature Language="F#" Value="member this.ServicePrincipalId : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.AzureDataLakeStoreLinkedService.ServicePrincipalId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            省略可能。 Azure Data Lake Store アカウントに対する認証に使用されるアプリケーションの ID。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServicePrincipalKey">
      <MemberSignature Language="C#" Value="public string ServicePrincipalKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServicePrincipalKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.AzureDataLakeStoreLinkedService.ServicePrincipalKey" />
      <MemberSignature Language="VB.NET" Value="Public Property ServicePrincipalKey As String" />
      <MemberSignature Language="F#" Value="member this.ServicePrincipalKey : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.AzureDataLakeStoreLinkedService.ServicePrincipalKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            省略可能。 Azure Data Lake Store アカウントに対する認証に使用されるアプリケーションのキー。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SessionId">
      <MemberSignature Language="C#" Value="public string SessionId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SessionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.AzureDataLakeStoreLinkedService.SessionId" />
      <MemberSignature Language="VB.NET" Value="Public Property SessionId As String" />
      <MemberSignature Language="F#" Value="member this.SessionId : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.AzureDataLakeStoreLinkedService.SessionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            OAuth 承認セッションからの OAuth セッション ID です。
            各セッション ID は一意と 1 回のみ使用できます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubscriptionId">
      <MemberSignature Language="C#" Value="public string SubscriptionId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SubscriptionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.AzureDataLakeStoreLinkedService.SubscriptionId" />
      <MemberSignature Language="VB.NET" Value="Public Property SubscriptionId As String" />
      <MemberSignature Language="F#" Value="member this.SubscriptionId : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.AzureDataLakeStoreLinkedService.SubscriptionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            省略可能。 Data Lake Store アカウント サブスクリプション ID (Data Factory アカウントとは異なる) 場合です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Tenant">
      <MemberSignature Language="C#" Value="public string Tenant { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Tenant" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.AzureDataLakeStoreLinkedService.Tenant" />
      <MemberSignature Language="VB.NET" Value="Public Property Tenant As String" />
      <MemberSignature Language="F#" Value="member this.Tenant : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.AzureDataLakeStoreLinkedService.Tenant" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            省略可能。 名前またはサービス プリンシパルが属しているテナントの ID。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>