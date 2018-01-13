<Type Name="JobDataPath" FullName="Microsoft.Azure.Management.DataLake.Analytics.Models.JobDataPath">
  <TypeSignature Language="C#" Value="public class JobDataPath" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JobDataPath extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Analytics.Models.JobDataPath" />
  <TypeSignature Language="VB.NET" Value="Public Class JobDataPath" />
  <TypeSignature Language="F#" Value="type JobDataPath = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Data Lake Analytics ジョブのデータ パス アイテム。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobDataPath ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.JobDataPath.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            JobDataPath クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobDataPath (Nullable&lt;Guid&gt; jobId = null, string command = null, System.Collections.Generic.IList&lt;string&gt; paths = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;valuetype System.Guid&gt; jobId, string command, class System.Collections.Generic.IList`1&lt;string&gt; paths) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.JobDataPath.#ctor(System.Nullable{System.Guid},System.String,System.Collections.Generic.IList{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional jobId As Nullable(Of Guid) = null, Optional command As String = null, Optional paths As IList(Of String) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Analytics.Models.JobDataPath : Nullable&lt;Guid&gt; * string * System.Collections.Generic.IList&lt;string&gt; -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.JobDataPath" Usage="new Microsoft.Azure.Management.DataLake.Analytics.Models.JobDataPath (jobId, command, paths)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="jobId" Type="System.Nullable&lt;System.Guid&gt;" />
        <Parameter Name="command" Type="System.String" />
        <Parameter Name="paths" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="jobId">このデータは、ジョブの id。</param>
        <param name="command">このジョブのデータに関連するコマンドです。</param>
        <param name="paths">すべてのジョブ データへのパスの一覧。</param>
        <summary>
            JobDataPath クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Command">
      <MemberSignature Language="C#" Value="public string Command { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Command" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobDataPath.Command" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Command As String" />
      <MemberSignature Language="F#" Value="member this.Command : string" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobDataPath.Command" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="command")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            このジョブのデータに関連するコマンドを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JobId">
      <MemberSignature Language="C#" Value="public Nullable&lt;Guid&gt; JobId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.Guid&gt; JobId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobDataPath.JobId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property JobId As Nullable(Of Guid)" />
      <MemberSignature Language="F#" Value="member this.JobId : Nullable&lt;Guid&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobDataPath.JobId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="jobId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Guid&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            このデータは、ジョブの id を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Paths">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Paths { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Paths" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobDataPath.Paths" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Paths As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Paths : System.Collections.Generic.IList&lt;string&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobDataPath.Paths" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="paths")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            すべてのジョブ データへのパスの一覧を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>