<Type Name="JobsListOutputFilesOptions" FullName="Microsoft.Azure.Management.BatchAI.Models.JobsListOutputFilesOptions">
  <TypeSignature Language="C#" Value="public class JobsListOutputFilesOptions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JobsListOutputFilesOptions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BatchAI.Models.JobsListOutputFilesOptions" />
  <TypeSignature Language="VB.NET" Value="Public Class JobsListOutputFilesOptions" />
  <TypeSignature Language="F#" Value="type JobsListOutputFilesOptions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            ListOutputFiles 操作に追加のパラメーターです。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobsListOutputFilesOptions ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.JobsListOutputFilesOptions.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            JobsListOutputFilesOptions クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobsListOutputFilesOptions (string outputdirectoryid, Nullable&lt;int&gt; linkexpiryinminutes = null, Nullable&lt;int&gt; maxResults = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string outputdirectoryid, valuetype System.Nullable`1&lt;int32&gt; linkexpiryinminutes, valuetype System.Nullable`1&lt;int32&gt; maxResults) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.JobsListOutputFilesOptions.#ctor(System.String,System.Nullable{System.Int32},System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (outputdirectoryid As String, Optional linkexpiryinminutes As Nullable(Of Integer) = null, Optional maxResults As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.BatchAI.Models.JobsListOutputFilesOptions : string * Nullable&lt;int&gt; * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Management.BatchAI.Models.JobsListOutputFilesOptions" Usage="new Microsoft.Azure.Management.BatchAI.Models.JobsListOutputFilesOptions (outputdirectoryid, linkexpiryinminutes, maxResults)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="outputdirectoryid" Type="System.String" />
        <Parameter Name="linkexpiryinminutes" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="maxResults" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="outputdirectoryid">ジョブの id は、ディレクトリを出力します。
            これは、OutputDirectory--&gt;ジョブの作成中に、ユーザーによって指定された id パラメーター。</param>
        <param name="linkexpiryinminutes">(分) のダウンロードのリンクは期限切れの数。</param>
        <param name="maxResults">応答で返されるアイテムの最大数。 最大で 1000 のファイルが返されます。</param>
        <summary>
            JobsListOutputFilesOptions クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Linkexpiryinminutes">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Linkexpiryinminutes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Linkexpiryinminutes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.JobsListOutputFilesOptions.Linkexpiryinminutes" />
      <MemberSignature Language="VB.NET" Value="Public Property Linkexpiryinminutes As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Linkexpiryinminutes : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.JobsListOutputFilesOptions.Linkexpiryinminutes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または分のダウンロードのリンクは期限切れの数を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxResults">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaxResults { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaxResults" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.JobsListOutputFilesOptions.MaxResults" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxResults As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaxResults : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.JobsListOutputFilesOptions.MaxResults" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または応答で返されるアイテムの最大数を設定します。
            最大で 1000 のファイルが返されます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Outputdirectoryid">
      <MemberSignature Language="C#" Value="public string Outputdirectoryid { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Outputdirectoryid" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.JobsListOutputFilesOptions.Outputdirectoryid" />
      <MemberSignature Language="VB.NET" Value="Public Property Outputdirectoryid As String" />
      <MemberSignature Language="F#" Value="member this.Outputdirectoryid : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.JobsListOutputFilesOptions.Outputdirectoryid" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはジョブの出力ディレクトリの id を設定します。 これは、OutputDirectory--&amp;gt; ジョブの作成中に、ユーザーによって指定された id パラメーター。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.JobsListOutputFilesOptions.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="jobsListOutputFilesOptions.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
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