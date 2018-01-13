<Type Name="OperationListResult" FullName="Microsoft.Azure.Management.Monitor.Management.Models.OperationListResult">
  <TypeSignature Language="C#" Value="public class OperationListResult" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit OperationListResult extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Monitor.Management.Models.OperationListResult" />
  <TypeSignature Language="VB.NET" Value="Public Class OperationListResult" />
  <TypeSignature Language="F#" Value="type OperationListResult = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
    <AssemblyVersion>0.18.0.0</AssemblyVersion>
    <AssemblyVersion>0.18.1.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Microsoft.insights に操作の一覧を表示する要求の結果です。 操作と次の結果セットを取得する URL リンクの一覧が含まれています。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OperationListResult ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.OperationListResult.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            OperationListResult クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OperationListResult (System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Management.Models.Operation&gt; value = null, string nextLink = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Monitor.Management.Models.Operation&gt; value, string nextLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.OperationListResult.#ctor(System.Collections.Generic.IList{Microsoft.Azure.Management.Monitor.Management.Models.Operation},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional value As IList(Of Operation) = null, Optional nextLink As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Monitor.Management.Models.OperationListResult : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Management.Models.Operation&gt; * string -&gt; Microsoft.Azure.Management.Monitor.Management.Models.OperationListResult" Usage="new Microsoft.Azure.Management.Monitor.Management.Models.OperationListResult (value, nextLink)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="value" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Management.Models.Operation&gt;" />
        <Parameter Name="nextLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="value">Microsoft.insights にプロバイダーによってサポートされる操作の一覧です。</param>
        <param name="nextLink">いずれかを使用する必要がある場合、次の操作のセットの結果のリストを取得する URL です。</param>
        <summary>
            OperationListResult クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NextLink">
      <MemberSignature Language="C#" Value="public string NextLink { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NextLink" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.OperationListResult.NextLink" />
      <MemberSignature Language="VB.NET" Value="Public Property NextLink As String" />
      <MemberSignature Language="F#" Value="member this.NextLink : string with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.OperationListResult.NextLink" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="nextLink")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはいずれかを使用する必要がある場合、次の操作のセットの結果のリストを取得する URL を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Value">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Management.Models.Operation&gt; Value { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Monitor.Management.Models.Operation&gt; Value" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.OperationListResult.Value" />
      <MemberSignature Language="VB.NET" Value="Public Property Value As IList(Of Operation)" />
      <MemberSignature Language="F#" Value="member this.Value : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Management.Models.Operation&gt; with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.OperationListResult.Value" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="value")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Management.Models.Operation&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または microsoft.insights にプロバイダーによってサポートされる操作の一覧を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>