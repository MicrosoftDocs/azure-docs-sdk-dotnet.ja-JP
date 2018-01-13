<Type Name="DataMaskingPolicy" FullName="Microsoft.Azure.Management.Sql.Models.DataMaskingPolicy">
  <TypeSignature Language="C#" Value="public class DataMaskingPolicy : Microsoft.Azure.Management.Sql.Models.ProxyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DataMaskingPolicy extends Microsoft.Azure.Management.Sql.Models.ProxyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Models.DataMaskingPolicy" />
  <TypeSignature Language="VB.NET" Value="Public Class DataMaskingPolicy&#xA;Inherits ProxyResource" />
  <TypeSignature Language="F#" Value="type DataMaskingPolicy = class&#xA;    inherit ProxyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Sql.Models.ProxyResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            データベース データ マスキング ポリシーを表します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataMaskingPolicy ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.DataMaskingPolicy.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            DataMaskingPolicy クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataMaskingPolicy (Microsoft.Azure.Management.Sql.Models.DataMaskingState dataMaskingState, string id = null, string name = null, string type = null, string exemptPrincipals = null, string applicationPrincipals = null, string maskingLevel = null, string location = null, string kind = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.Azure.Management.Sql.Models.DataMaskingState dataMaskingState, string id, string name, string type, string exemptPrincipals, string applicationPrincipals, string maskingLevel, string location, string kind) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.DataMaskingPolicy.#ctor(Microsoft.Azure.Management.Sql.Models.DataMaskingState,System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.Models.DataMaskingPolicy : Microsoft.Azure.Management.Sql.Models.DataMaskingState * string * string * string * string * string * string * string * string -&gt; Microsoft.Azure.Management.Sql.Models.DataMaskingPolicy" Usage="new Microsoft.Azure.Management.Sql.Models.DataMaskingPolicy (dataMaskingState, id, name, type, exemptPrincipals, applicationPrincipals, maskingLevel, location, kind)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="dataMaskingState" Type="Microsoft.Azure.Management.Sql.Models.DataMaskingState" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="exemptPrincipals" Type="System.String" />
        <Parameter Name="applicationPrincipals" Type="System.String" />
        <Parameter Name="maskingLevel" Type="System.String" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="kind" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="dataMaskingState">データ マスク ポリシーの状態。 使用可能な値が含まれます: '無効'、'Enabled'</param>
        <param name="id">リソースの ID</param>
        <param name="name">リソース名。</param>
        <param name="type">リソースの種類。</param>
        <param name="exemptPrincipals">除外対象プリンシパルの一覧です。
            データベース ユーザーがデータ マスキング ポリシーは適用されませんのセミコロンで区切った一覧を指定します。 指定されたユーザーは、データベース クエリのすべてのマスクなしの結果のデータを受信します。</param>
        <param name="applicationPrincipals">アプリケーションのプリンシパルの一覧。 これはレガシ パラメーターであり、不要になった。</param>
        <param name="maskingLevel">マスキング レベルです。 これはレガシ パラメーターであり、不要になった。</param>
        <param name="location">データ マスク ポリシーの場所です。</param>
        <param name="kind">データ マスキング ポリシーの種類。 Azure ポータルで使用されるメタデータ。</param>
        <summary>
            DataMaskingPolicy クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationPrincipals">
      <MemberSignature Language="C#" Value="public string ApplicationPrincipals { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ApplicationPrincipals" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DataMaskingPolicy.ApplicationPrincipals" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationPrincipals As String" />
      <MemberSignature Language="F#" Value="member this.ApplicationPrincipals : string" Usage="Microsoft.Azure.Management.Sql.Models.DataMaskingPolicy.ApplicationPrincipals" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.applicationPrincipals")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            アプリケーションのプリンシパルの一覧を取得します。 これはレガシ パラメーターであり、不要になった。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataMaskingState">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.Models.DataMaskingState DataMaskingState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Sql.Models.DataMaskingState DataMaskingState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DataMaskingPolicy.DataMaskingState" />
      <MemberSignature Language="VB.NET" Value="Public Property DataMaskingState As DataMaskingState" />
      <MemberSignature Language="F#" Value="member this.DataMaskingState : Microsoft.Azure.Management.Sql.Models.DataMaskingState with get, set" Usage="Microsoft.Azure.Management.Sql.Models.DataMaskingPolicy.DataMaskingState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.dataMaskingState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.DataMaskingState</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはデータ マスキング ポリシーの状態を設定します。 使用可能な値が含まれます: '無効'、'Enabled'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExemptPrincipals">
      <MemberSignature Language="C#" Value="public string ExemptPrincipals { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ExemptPrincipals" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DataMaskingPolicy.ExemptPrincipals" />
      <MemberSignature Language="VB.NET" Value="Public Property ExemptPrincipals As String" />
      <MemberSignature Language="F#" Value="member this.ExemptPrincipals : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.DataMaskingPolicy.ExemptPrincipals" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.exemptPrincipals")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または除外のプリンシパルの一覧を設定します。 データベース ユーザーがデータ マスキング ポリシーは適用されませんのセミコロンで区切った一覧を指定します。 指定されたユーザーは、データベース クエリのすべてのマスクなしの結果のデータを受信します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Kind">
      <MemberSignature Language="C#" Value="public string Kind { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Kind" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DataMaskingPolicy.Kind" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Kind As String" />
      <MemberSignature Language="F#" Value="member this.Kind : string" Usage="Microsoft.Azure.Management.Sql.Models.DataMaskingPolicy.Kind" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="kind")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            データ マスキング ポリシーの種類を取得します。 Azure ポータルで使用されるメタデータ。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Location">
      <MemberSignature Language="C#" Value="public string Location { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Location" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DataMaskingPolicy.Location" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Location As String" />
      <MemberSignature Language="F#" Value="member this.Location : string" Usage="Microsoft.Azure.Management.Sql.Models.DataMaskingPolicy.Location" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="location")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            データ マスク ポリシーの場所を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaskingLevel">
      <MemberSignature Language="C#" Value="public string MaskingLevel { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MaskingLevel" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DataMaskingPolicy.MaskingLevel" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MaskingLevel As String" />
      <MemberSignature Language="F#" Value="member this.MaskingLevel : string" Usage="Microsoft.Azure.Management.Sql.Models.DataMaskingPolicy.MaskingLevel" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.maskingLevel")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            マスキング レベルを取得します。 これはレガシ パラメーターであり、不要になった。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.DataMaskingPolicy.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="dataMaskingPolicy.Validate " />
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