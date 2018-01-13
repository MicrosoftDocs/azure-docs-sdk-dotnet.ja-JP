<Type Name="PipelinesOperationsExtensions" FullName="Microsoft.Azure.Management.DataFactory.PipelinesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class PipelinesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit PipelinesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.PipelinesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module PipelinesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type PipelinesOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
    <AssemblyVersion>0.2.0.0</AssemblyVersion>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            PipelinesOperations の拡張メソッド。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactory.Models.PipelineResource CreateOrUpdate (this Microsoft.Azure.Management.DataFactory.IPipelinesOperations operations, string resourceGroupName, string factoryName, string pipelineName, Microsoft.Azure.Management.DataFactory.Models.PipelineResource pipeline, string ifMatch = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactory.Models.PipelineResource CreateOrUpdate(class Microsoft.Azure.Management.DataFactory.IPipelinesOperations operations, string resourceGroupName, string factoryName, string pipelineName, class Microsoft.Azure.Management.DataFactory.Models.PipelineResource pipeline, string ifMatch) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.PipelinesOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.DataFactory.IPipelinesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataFactory.Models.PipelineResource,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IPipelinesOperations, resourceGroupName As String, factoryName As String, pipelineName As String, pipeline As PipelineResource, Optional ifMatch As String = null) As PipelineResource" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.DataFactory.IPipelinesOperations * string * string * string * Microsoft.Azure.Management.DataFactory.Models.PipelineResource * string -&gt; Microsoft.Azure.Management.DataFactory.Models.PipelineResource" Usage="Microsoft.Azure.Management.DataFactory.PipelinesOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, factoryName, pipelineName, pipeline, ifMatch)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.PipelineResource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IPipelinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="pipelineName" Type="System.String" />
        <Parameter Name="pipeline" Type="Microsoft.Azure.Management.DataFactory.Models.PipelineResource" />
        <Parameter Name="ifMatch" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループ名。
            </param>
        <param name="factoryName">
            ファクトリの名前です。
            </param>
        <param name="pipelineName">
            パイプラインの名前です。
            </param>
        <param name="pipeline">
            リソース定義をパイプラインです。
            </param>
        <param name="ifMatch">
            パイプラインのエンティティの ETag です。  更新については、対象の既存のエンティティが一致していることもできますのみ指定する必要があります * の無条件更新します。
            </param>
        <summary>
            作成するか、パイプラインを更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.PipelineResource&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.DataFactory.IPipelinesOperations operations, string resourceGroupName, string factoryName, string pipelineName, Microsoft.Azure.Management.DataFactory.Models.PipelineResource pipeline, string ifMatch = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactory.Models.PipelineResource&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.DataFactory.IPipelinesOperations operations, string resourceGroupName, string factoryName, string pipelineName, class Microsoft.Azure.Management.DataFactory.Models.PipelineResource pipeline, string ifMatch, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.PipelinesOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.DataFactory.IPipelinesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataFactory.Models.PipelineResource,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.DataFactory.IPipelinesOperations * string * string * string * Microsoft.Azure.Management.DataFactory.Models.PipelineResource * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.PipelineResource&gt;" Usage="Microsoft.Azure.Management.DataFactory.PipelinesOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, factoryName, pipelineName, pipeline, ifMatch, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataFactory.PipelinesOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.PipelineResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IPipelinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="pipelineName" Type="System.String" />
        <Parameter Name="pipeline" Type="Microsoft.Azure.Management.DataFactory.Models.PipelineResource" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループ名。
            </param>
        <param name="factoryName">
            ファクトリの名前です。
            </param>
        <param name="pipelineName">
            パイプラインの名前です。
            </param>
        <param name="pipeline">
            リソース定義をパイプラインです。
            </param>
        <param name="ifMatch">
            パイプラインのエンティティの ETag です。  更新については、対象の既存のエンティティが一致していることもできますのみ指定する必要があります * の無条件更新します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            作成するか、パイプラインを更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateRun">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactory.Models.CreateRunResponse CreateRun (this Microsoft.Azure.Management.DataFactory.IPipelinesOperations operations, string resourceGroupName, string factoryName, string pipelineName, System.Collections.Generic.IDictionary&lt;string,object&gt; parameters = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactory.Models.CreateRunResponse CreateRun(class Microsoft.Azure.Management.DataFactory.IPipelinesOperations operations, string resourceGroupName, string factoryName, string pipelineName, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.PipelinesOperationsExtensions.CreateRun(Microsoft.Azure.Management.DataFactory.IPipelinesOperations,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateRun (operations As IPipelinesOperations, resourceGroupName As String, factoryName As String, pipelineName As String, Optional parameters As IDictionary(Of String, Object) = null) As CreateRunResponse" />
      <MemberSignature Language="F#" Value="static member CreateRun : Microsoft.Azure.Management.DataFactory.IPipelinesOperations * string * string * string * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; Microsoft.Azure.Management.DataFactory.Models.CreateRunResponse" Usage="Microsoft.Azure.Management.DataFactory.PipelinesOperationsExtensions.CreateRun (operations, resourceGroupName, factoryName, pipelineName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.CreateRunResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IPipelinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="pipelineName" Type="System.String" />
        <Parameter Name="parameters" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループ名。
            </param>
        <param name="factoryName">
            ファクトリの名前です。
            </param>
        <param name="pipelineName">
            パイプラインの名前です。
            </param>
        <param name="parameters">
            パイプラインのパラメーターを実行します。
            </param>
        <summary>
            パイプラインの実行を作成します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateRunAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.CreateRunResponse&gt; CreateRunAsync (this Microsoft.Azure.Management.DataFactory.IPipelinesOperations operations, string resourceGroupName, string factoryName, string pipelineName, System.Collections.Generic.IDictionary&lt;string,object&gt; parameters = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactory.Models.CreateRunResponse&gt; CreateRunAsync(class Microsoft.Azure.Management.DataFactory.IPipelinesOperations operations, string resourceGroupName, string factoryName, string pipelineName, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.PipelinesOperationsExtensions.CreateRunAsync(Microsoft.Azure.Management.DataFactory.IPipelinesOperations,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.Object},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateRunAsync : Microsoft.Azure.Management.DataFactory.IPipelinesOperations * string * string * string * System.Collections.Generic.IDictionary&lt;string, obj&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.CreateRunResponse&gt;" Usage="Microsoft.Azure.Management.DataFactory.PipelinesOperationsExtensions.CreateRunAsync (operations, resourceGroupName, factoryName, pipelineName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataFactory.PipelinesOperationsExtensions/&lt;CreateRunAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.CreateRunResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IPipelinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="pipelineName" Type="System.String" />
        <Parameter Name="parameters" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループ名。
            </param>
        <param name="factoryName">
            ファクトリの名前です。
            </param>
        <param name="pipelineName">
            パイプラインの名前です。
            </param>
        <param name="parameters">
            パイプラインのパラメーターを実行します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            パイプラインの実行を作成します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.DataFactory.IPipelinesOperations operations, string resourceGroupName, string factoryName, string pipelineName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.DataFactory.IPipelinesOperations operations, string resourceGroupName, string factoryName, string pipelineName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.PipelinesOperationsExtensions.Delete(Microsoft.Azure.Management.DataFactory.IPipelinesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IPipelinesOperations, resourceGroupName As String, factoryName As String, pipelineName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.DataFactory.IPipelinesOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.DataFactory.PipelinesOperationsExtensions.Delete (operations, resourceGroupName, factoryName, pipelineName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IPipelinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="pipelineName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループ名。
            </param>
        <param name="factoryName">
            ファクトリの名前です。
            </param>
        <param name="pipelineName">
            パイプラインの名前です。
            </param>
        <summary>
            パイプラインを削除します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.DataFactory.IPipelinesOperations operations, string resourceGroupName, string factoryName, string pipelineName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.DataFactory.IPipelinesOperations operations, string resourceGroupName, string factoryName, string pipelineName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.PipelinesOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.DataFactory.IPipelinesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.DataFactory.IPipelinesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.DataFactory.PipelinesOperationsExtensions.DeleteAsync (operations, resourceGroupName, factoryName, pipelineName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataFactory.PipelinesOperationsExtensions/&lt;DeleteAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IPipelinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="pipelineName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループ名。
            </param>
        <param name="factoryName">
            ファクトリの名前です。
            </param>
        <param name="pipelineName">
            パイプラインの名前です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            パイプラインを削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactory.Models.PipelineResource Get (this Microsoft.Azure.Management.DataFactory.IPipelinesOperations operations, string resourceGroupName, string factoryName, string pipelineName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactory.Models.PipelineResource Get(class Microsoft.Azure.Management.DataFactory.IPipelinesOperations operations, string resourceGroupName, string factoryName, string pipelineName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.PipelinesOperationsExtensions.Get(Microsoft.Azure.Management.DataFactory.IPipelinesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IPipelinesOperations, resourceGroupName As String, factoryName As String, pipelineName As String) As PipelineResource" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.DataFactory.IPipelinesOperations * string * string * string -&gt; Microsoft.Azure.Management.DataFactory.Models.PipelineResource" Usage="Microsoft.Azure.Management.DataFactory.PipelinesOperationsExtensions.Get (operations, resourceGroupName, factoryName, pipelineName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.PipelineResource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IPipelinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="pipelineName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループ名。
            </param>
        <param name="factoryName">
            ファクトリの名前です。
            </param>
        <param name="pipelineName">
            パイプラインの名前です。
            </param>
        <summary>
            パイプラインを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.PipelineResource&gt; GetAsync (this Microsoft.Azure.Management.DataFactory.IPipelinesOperations operations, string resourceGroupName, string factoryName, string pipelineName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactory.Models.PipelineResource&gt; GetAsync(class Microsoft.Azure.Management.DataFactory.IPipelinesOperations operations, string resourceGroupName, string factoryName, string pipelineName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.PipelinesOperationsExtensions.GetAsync(Microsoft.Azure.Management.DataFactory.IPipelinesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.DataFactory.IPipelinesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.PipelineResource&gt;" Usage="Microsoft.Azure.Management.DataFactory.PipelinesOperationsExtensions.GetAsync (operations, resourceGroupName, factoryName, pipelineName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataFactory.PipelinesOperationsExtensions/&lt;GetAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.PipelineResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IPipelinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="pipelineName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループ名。
            </param>
        <param name="factoryName">
            ファクトリの名前です。
            </param>
        <param name="pipelineName">
            パイプラインの名前です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            パイプラインを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByFactory">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.PipelineResource&gt; ListByFactory (this Microsoft.Azure.Management.DataFactory.IPipelinesOperations operations, string resourceGroupName, string factoryName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataFactory.Models.PipelineResource&gt; ListByFactory(class Microsoft.Azure.Management.DataFactory.IPipelinesOperations operations, string resourceGroupName, string factoryName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.PipelinesOperationsExtensions.ListByFactory(Microsoft.Azure.Management.DataFactory.IPipelinesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByFactory (operations As IPipelinesOperations, resourceGroupName As String, factoryName As String) As IPage(Of PipelineResource)" />
      <MemberSignature Language="F#" Value="static member ListByFactory : Microsoft.Azure.Management.DataFactory.IPipelinesOperations * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.PipelineResource&gt;" Usage="Microsoft.Azure.Management.DataFactory.PipelinesOperationsExtensions.ListByFactory (operations, resourceGroupName, factoryName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.PipelineResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IPipelinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループ名。
            </param>
        <param name="factoryName">
            ファクトリの名前です。
            </param>
        <summary>
            パイプラインの一覧を示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByFactoryAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.PipelineResource&gt;&gt; ListByFactoryAsync (this Microsoft.Azure.Management.DataFactory.IPipelinesOperations operations, string resourceGroupName, string factoryName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataFactory.Models.PipelineResource&gt;&gt; ListByFactoryAsync(class Microsoft.Azure.Management.DataFactory.IPipelinesOperations operations, string resourceGroupName, string factoryName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.PipelinesOperationsExtensions.ListByFactoryAsync(Microsoft.Azure.Management.DataFactory.IPipelinesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByFactoryAsync : Microsoft.Azure.Management.DataFactory.IPipelinesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.PipelineResource&gt;&gt;" Usage="Microsoft.Azure.Management.DataFactory.PipelinesOperationsExtensions.ListByFactoryAsync (operations, resourceGroupName, factoryName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataFactory.PipelinesOperationsExtensions/&lt;ListByFactoryAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.PipelineResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IPipelinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループ名。
            </param>
        <param name="factoryName">
            ファクトリの名前です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            パイプラインの一覧を示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByFactoryNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.PipelineResource&gt; ListByFactoryNext (this Microsoft.Azure.Management.DataFactory.IPipelinesOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataFactory.Models.PipelineResource&gt; ListByFactoryNext(class Microsoft.Azure.Management.DataFactory.IPipelinesOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.PipelinesOperationsExtensions.ListByFactoryNext(Microsoft.Azure.Management.DataFactory.IPipelinesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByFactoryNext (operations As IPipelinesOperations, nextPageLink As String) As IPage(Of PipelineResource)" />
      <MemberSignature Language="F#" Value="static member ListByFactoryNext : Microsoft.Azure.Management.DataFactory.IPipelinesOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.PipelineResource&gt;" Usage="Microsoft.Azure.Management.DataFactory.PipelinesOperationsExtensions.ListByFactoryNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.PipelineResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IPipelinesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="nextPageLink">
            一覧表示操作に成功した呼び出しからの NextLink です。
            </param>
        <summary>
            パイプラインの一覧を示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByFactoryNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.PipelineResource&gt;&gt; ListByFactoryNextAsync (this Microsoft.Azure.Management.DataFactory.IPipelinesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataFactory.Models.PipelineResource&gt;&gt; ListByFactoryNextAsync(class Microsoft.Azure.Management.DataFactory.IPipelinesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.PipelinesOperationsExtensions.ListByFactoryNextAsync(Microsoft.Azure.Management.DataFactory.IPipelinesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByFactoryNextAsync : Microsoft.Azure.Management.DataFactory.IPipelinesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.PipelineResource&gt;&gt;" Usage="Microsoft.Azure.Management.DataFactory.PipelinesOperationsExtensions.ListByFactoryNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataFactory.PipelinesOperationsExtensions/&lt;ListByFactoryNextAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.PipelineResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IPipelinesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="nextPageLink">
            一覧表示操作に成功した呼び出しからの NextLink です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            パイプラインの一覧を示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>