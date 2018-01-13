<Type Name="LinkedServiceProperties" FullName="Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceProperties">
  <TypeSignature Language="C#" Value="public class LinkedServiceProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit LinkedServiceProperties extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceProperties" />
  <TypeSignature Language="VB.NET" Value="Public Class LinkedServiceProperties" />
  <TypeSignature Language="F#" Value="type LinkedServiceProperties = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            データ ファクトリの linkedService プロパティです。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public LinkedServiceProperties ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceProperties.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            LinkedServiceProperties クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public LinkedServiceProperties (string type, string typeProperties);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string type, string typeProperties) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceProperties.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (type As String, typeProperties As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceProperties : string * string -&gt; Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceProperties" Usage="new Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceProperties (type, typeProperties)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="typeProperties" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="type">To be added.</param>
        <param name="typeProperties">To be added.</param>
        <summary>
            必須の引数で LinkedServiceProperties クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Description">
      <MemberSignature Language="C#" Value="public string Description { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Description" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceProperties.Description" />
      <MemberSignature Language="VB.NET" Value="Public Property Description As String" />
      <MemberSignature Language="F#" Value="member this.Description : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceProperties.Description" />
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
            省略可能。 データ ファクトリの linkedService 説明します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ErrorMessage">
      <MemberSignature Language="C#" Value="public string ErrorMessage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ErrorMessage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceProperties.ErrorMessage" />
      <MemberSignature Language="VB.NET" Value="Public Property ErrorMessage As String" />
      <MemberSignature Language="F#" Value="member this.ErrorMessage : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceProperties.ErrorMessage" />
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
            省略可能。 LinkedService の要求の処理のエラーです。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HubName">
      <MemberSignature Language="C#" Value="public string HubName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string HubName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceProperties.HubName" />
      <MemberSignature Language="VB.NET" Value="Public Property HubName As String" />
      <MemberSignature Language="F#" Value="member this.HubName : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceProperties.HubName" />
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
            省略可能。 リンクされたサービスがこのハブの名前に属しています。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceProperties.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceProperties.ProvisioningState" />
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
            省略可能。 リンクされたサービスのプロビジョニングの状態。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public string Type { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceProperties.Type" />
      <MemberSignature Language="VB.NET" Value="Public Property Type As String" />
      <MemberSignature Language="F#" Value="member this.Type : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceProperties.Type" />
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
            必須。 リンクされたサービスの型。 ビルドで ADF 型または型の名前登録、ユーザーによってとデータ ファクトリに使用できるこのリンクされたサービスのメンバーであります。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TypeProperties">
      <MemberSignature Language="C#" Value="public string TypeProperties { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TypeProperties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceProperties.TypeProperties" />
      <MemberSignature Language="VB.NET" Value="Public Property TypeProperties As String" />
      <MemberSignature Language="F#" Value="member this.TypeProperties : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceProperties.TypeProperties" />
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
            必須。 リンクされたサービスに固有のプロパティを入力します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>