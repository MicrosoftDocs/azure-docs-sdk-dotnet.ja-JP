<Type Name="MultiInstanceSettings" FullName="Microsoft.Azure.Batch.MultiInstanceSettings">
  <TypeSignature Language="C#" Value="public class MultiInstanceSettings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MultiInstanceSettings extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.MultiInstanceSettings" />
  <TypeSignature Language="VB.NET" Value="Public Class MultiInstanceSettings" />
  <TypeSignature Language="F#" Value="type MultiInstanceSettings = class&#xA;    interface ITransportObjectProvider&lt;MultiInstanceSettings&gt;&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            マルチ インスタンスのタスクを実行する方法を指定する設定です。 マルチ インスタンスのタスクは通常、MPI タスクをサポートするために使用されます。 詳細については、https://azure.microsoft.com/documentation/articles/batch-mpi/ を参照してください。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MultiInstanceSettings (string coordinationCommandLine, Nullable&lt;int&gt; numberOfInstances = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string coordinationCommandLine, valuetype System.Nullable`1&lt;int32&gt; numberOfInstances) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.MultiInstanceSettings.#ctor(System.String,System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (coordinationCommandLine As String, Optional numberOfInstances As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.MultiInstanceSettings : string * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Batch.MultiInstanceSettings" Usage="new Microsoft.Azure.Batch.MultiInstanceSettings (coordinationCommandLine, numberOfInstances)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="coordinationCommandLine" Type="System.String" />
        <Parameter Name="numberOfInstances" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="coordinationCommandLine">サブタスクを調整するためのコンピューティング ノードのインスタンスで実行するコマンドです。</param>
        <param name="numberOfInstances">マルチ インスタンスのタスクで必要なコンピューティング ノードの数。</param>
        <summary>
            <see cref="T:Microsoft.Azure.Batch.MultiInstanceSettings" /> クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CommonResourceFiles">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.ResourceFile&gt; CommonResourceFiles { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.ResourceFile&gt; CommonResourceFiles" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.MultiInstanceSettings.CommonResourceFiles" />
      <MemberSignature Language="VB.NET" Value="Public Property CommonResourceFiles As IList(Of ResourceFile)" />
      <MemberSignature Language="F#" Value="member this.CommonResourceFiles : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.ResourceFile&gt; with get, set" Usage="Microsoft.Azure.Batch.MultiInstanceSettings.CommonResourceFiles" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.ResourceFile&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または調整のコマンドラインを実行する前に、バッチ サービスをダウンロードするファイルの一覧を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            一般的なリソース ファイルとリソース ファイルのタスクの違いは、プライマリののみタスク リソース ファイルがダウンロードされ、プライマリを含むすべてのサブタスクの一般的なリソース ファイルにダウンロードされます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CoordinationCommandLine">
      <MemberSignature Language="C#" Value="public string CoordinationCommandLine { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CoordinationCommandLine" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.MultiInstanceSettings.CoordinationCommandLine" />
      <MemberSignature Language="VB.NET" Value="Public Property CoordinationCommandLine As String" />
      <MemberSignature Language="F#" Value="member this.CoordinationCommandLine : string with get, set" Usage="Microsoft.Azure.Batch.MultiInstanceSettings.CoordinationCommandLine" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはサブタスクを調整するためのコンピューティング ノードのインスタンスで実行するコマンドを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NumberOfInstances">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; NumberOfInstances { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; NumberOfInstances" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.MultiInstanceSettings.NumberOfInstances" />
      <MemberSignature Language="VB.NET" Value="Public Property NumberOfInstances As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.NumberOfInstances : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Batch.MultiInstanceSettings.NumberOfInstances" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または複数のインスタンスのタスクで必要なコンピューティング ノードの数を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>