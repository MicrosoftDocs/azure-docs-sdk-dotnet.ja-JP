<Type Name="AzureMLLinkedService" FullName="Microsoft.Azure.Management.DataFactories.Models.AzureMLLinkedService">
  <TypeSignature Language="C#" Value="public class AzureMLLinkedService : Microsoft.Azure.Management.DataFactories.Models.LinkedServiceTypeProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AzureMLLinkedService extends Microsoft.Azure.Management.DataFactories.Models.LinkedServiceTypeProperties" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.Models.AzureMLLinkedService" />
  <TypeSignature Language="VB.NET" Value="Public Class AzureMLLinkedService&#xA;Inherits LinkedServiceTypeProperties" />
  <TypeSignature Language="F#" Value="type AzureMLLinkedService = class&#xA;    inherit LinkedServiceTypeProperties" />
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
      <AttributeName>Microsoft.Azure.Management.DataFactories.Models.AdfTypeName("AzureML")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Azure ML Web サービスにリンクされたサービスを指定します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureMLLinkedService ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Models.AzureMLLinkedService.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            AzureMLLinkedService クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureMLLinkedService (string mlEndpoint, string apiKey);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string mlEndpoint, string apiKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Models.AzureMLLinkedService.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (mlEndpoint As String, apiKey As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactories.Models.AzureMLLinkedService : string * string -&gt; Microsoft.Azure.Management.DataFactories.Models.AzureMLLinkedService" Usage="new Microsoft.Azure.Management.DataFactories.Models.AzureMLLinkedService (mlEndpoint, apiKey)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="mlEndpoint" Type="System.String" />
        <Parameter Name="apiKey" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="mlEndpoint">To be added.</param>
        <param name="apiKey">To be added.</param>
        <summary>
            必須の引数で AzureMLLinkedService クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApiKey">
      <MemberSignature Language="C#" Value="public string ApiKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ApiKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.AzureMLLinkedService.ApiKey" />
      <MemberSignature Language="VB.NET" Value="Public Property ApiKey As String" />
      <MemberSignature Language="F#" Value="member this.ApiKey : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.AzureMLLinkedService.ApiKey" />
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
            必須。 Azure ML モデル エンドポイントにアクセスするために API キー。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MlEndpoint">
      <MemberSignature Language="C#" Value="public string MlEndpoint { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MlEndpoint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.AzureMLLinkedService.MlEndpoint" />
      <MemberSignature Language="VB.NET" Value="Public Property MlEndpoint As String" />
      <MemberSignature Language="F#" Value="member this.MlEndpoint : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.AzureMLLinkedService.MlEndpoint" />
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
            必須。 Azure ML Web サービス エンドポイントのバッチ実行 REST の URL です。
            エンドポイントの形式を使用する必要があります: https://_地域_.services.azureml.net/workspaces/_workspace_id_/services/_service_id_ジョブ/? api バージョン = 2.0"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServicePrincipalId">
      <MemberSignature Language="C#" Value="public string ServicePrincipalId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServicePrincipalId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.AzureMLLinkedService.ServicePrincipalId" />
      <MemberSignature Language="VB.NET" Value="Public Property ServicePrincipalId As String" />
      <MemberSignature Language="F#" Value="member this.ServicePrincipalId : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.AzureMLLinkedService.ServicePrincipalId" />
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
            省略可能。 Azure ML web サービスの ARM ベース updateResourceEndpoint に対する認証に使用されるサービス プリンシパルの ID。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServicePrincipalKey">
      <MemberSignature Language="C#" Value="public string ServicePrincipalKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServicePrincipalKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.AzureMLLinkedService.ServicePrincipalKey" />
      <MemberSignature Language="VB.NET" Value="Public Property ServicePrincipalKey As String" />
      <MemberSignature Language="F#" Value="member this.ServicePrincipalKey : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.AzureMLLinkedService.ServicePrincipalKey" />
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
            省略可能。 Azure ML web サービスの ARM ベース updateResourceEndpoint に対する認証に使用されるサービス プリンシパルのキー。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Tenant">
      <MemberSignature Language="C#" Value="public string Tenant { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Tenant" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.AzureMLLinkedService.Tenant" />
      <MemberSignature Language="VB.NET" Value="Public Property Tenant As String" />
      <MemberSignature Language="F#" Value="member this.Tenant : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.AzureMLLinkedService.Tenant" />
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
    <Member MemberName="UpdateResourceEndpoint">
      <MemberSignature Language="C#" Value="public string UpdateResourceEndpoint { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string UpdateResourceEndpoint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.AzureMLLinkedService.UpdateResourceEndpoint" />
      <MemberSignature Language="VB.NET" Value="Public Property UpdateResourceEndpoint As String" />
      <MemberSignature Language="F#" Value="member this.UpdateResourceEndpoint : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.AzureMLLinkedService.UpdateResourceEndpoint" />
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
            省略可能。 Azure ML Web サービス エンドポイントの更新リソース REST の URL。
            エンドポイントの形式を使用する必要があります: https://management.azureml.net/workspaces/_workspace_id_/webservices/_service_id_/endpoints/_endpointName_です。
            このプロパティを使用して再トレーニング後で、エンドポイントを更新して<see cref="T:Microsoft.Azure.Management.DataFactories.Models.AzureMLUpdateResourceActivity" />です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>