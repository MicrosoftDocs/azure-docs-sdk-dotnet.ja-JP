<Type Name="IntegrationRuntimesOperationsExtensions" FullName="Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class IntegrationRuntimesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit IntegrationRuntimesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module IntegrationRuntimesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type IntegrationRuntimesOperationsExtensions = class" />
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
            IntegrationRuntimesOperations の拡張メソッド。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginStart">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeStatusResponse BeginStart (this Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeStatusResponse BeginStart(class Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.BeginStart(Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginStart (operations As IIntegrationRuntimesOperations, resourceGroupName As String, factoryName As String, integrationRuntimeName As String) As IntegrationRuntimeStatusResponse" />
      <MemberSignature Language="F#" Value="static member BeginStart : Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations * string * string * string -&gt; Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeStatusResponse" Usage="Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.BeginStart (operations, resourceGroupName, factoryName, integrationRuntimeName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeStatusResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="integrationRuntimeName" Type="System.String" />
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
        <param name="integrationRuntimeName">
            統合ランタイムの名前。
            </param>
        <summary>
            ManagedReserved 型統合ランタイムを起動します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginStartAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeStatusResponse&gt; BeginStartAsync (this Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeStatusResponse&gt; BeginStartAsync(class Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.BeginStartAsync(Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginStartAsync : Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeStatusResponse&gt;" Usage="Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.BeginStartAsync (operations, resourceGroupName, factoryName, integrationRuntimeName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions/&lt;BeginStartAsync&gt;d__31))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeStatusResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="integrationRuntimeName" Type="System.String" />
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
        <param name="integrationRuntimeName">
            統合ランタイムの名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            ManagedReserved 型統合ランタイムを起動します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginStop">
      <MemberSignature Language="C#" Value="public static void BeginStop (this Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginStop(class Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.BeginStop(Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginStop (operations As IIntegrationRuntimesOperations, resourceGroupName As String, factoryName As String, integrationRuntimeName As String)" />
      <MemberSignature Language="F#" Value="static member BeginStop : Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.BeginStop (operations, resourceGroupName, factoryName, integrationRuntimeName)" />
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
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="integrationRuntimeName" Type="System.String" />
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
        <param name="integrationRuntimeName">
            統合ランタイムの名前。
            </param>
        <summary>
            ManagedReserved 型統合ランタイムを停止します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginStopAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginStopAsync (this Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginStopAsync(class Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.BeginStopAsync(Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginStopAsync : Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.BeginStopAsync (operations, resourceGroupName, factoryName, integrationRuntimeName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions/&lt;BeginStopAsync&gt;d__33))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="integrationRuntimeName" Type="System.String" />
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
        <param name="integrationRuntimeName">
            統合ランタイムの名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            ManagedReserved 型統合ランタイムを停止します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeResource CreateOrUpdate (this Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName, Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeResource integrationRuntime, string ifMatch = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeResource CreateOrUpdate(class Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName, class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeResource integrationRuntime, string ifMatch) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeResource,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IIntegrationRuntimesOperations, resourceGroupName As String, factoryName As String, integrationRuntimeName As String, integrationRuntime As IntegrationRuntimeResource, Optional ifMatch As String = null) As IntegrationRuntimeResource" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations * string * string * string * Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeResource * string -&gt; Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeResource" Usage="Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, factoryName, integrationRuntimeName, integrationRuntime, ifMatch)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeResource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="integrationRuntimeName" Type="System.String" />
        <Parameter Name="integrationRuntime" Type="Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeResource" />
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
        <param name="integrationRuntimeName">
            統合ランタイムの名前。
            </param>
        <param name="integrationRuntime">
            統合ランタイムのリソース定義します。
            </param>
        <param name="ifMatch">
            統合ランタイム エンティティの ETag。 更新については、対象の既存のエンティティが一致していることもできますのみ指定する必要があります * の無条件更新します。
            </param>
        <summary>
            作成するか、統合ランタイムを更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeResource&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName, Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeResource integrationRuntime, string ifMatch = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeResource&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName, class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeResource integrationRuntime, string ifMatch, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeResource,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations * string * string * string * Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeResource * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeResource&gt;" Usage="Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, factoryName, integrationRuntimeName, integrationRuntime, ifMatch, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="integrationRuntimeName" Type="System.String" />
        <Parameter Name="integrationRuntime" Type="Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeResource" />
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
        <param name="integrationRuntimeName">
            統合ランタイムの名前。
            </param>
        <param name="integrationRuntime">
            統合ランタイムのリソース定義します。
            </param>
        <param name="ifMatch">
            統合ランタイム エンティティの ETag。 更新については、対象の既存のエンティティが一致していることもできますのみ指定する必要があります * の無条件更新します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            作成するか、統合ランタイムを更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.Delete(Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IIntegrationRuntimesOperations, resourceGroupName As String, factoryName As String, integrationRuntimeName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.Delete (operations, resourceGroupName, factoryName, integrationRuntimeName)" />
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
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="integrationRuntimeName" Type="System.String" />
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
        <param name="integrationRuntimeName">
            統合ランタイムの名前。
            </param>
        <summary>
            統合ランタイムを削除します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.DeleteAsync (operations, resourceGroupName, factoryName, integrationRuntimeName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions/&lt;DeleteAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="integrationRuntimeName" Type="System.String" />
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
        <param name="integrationRuntimeName">
            統合ランタイムの名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            統合ランタイムを削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeResource Get (this Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeResource Get(class Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.Get(Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IIntegrationRuntimesOperations, resourceGroupName As String, factoryName As String, integrationRuntimeName As String) As IntegrationRuntimeResource" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations * string * string * string -&gt; Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeResource" Usage="Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.Get (operations, resourceGroupName, factoryName, integrationRuntimeName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeResource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="integrationRuntimeName" Type="System.String" />
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
        <param name="integrationRuntimeName">
            統合ランタイムの名前。
            </param>
        <summary>
            統合ランタイムを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeResource&gt; GetAsync (this Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeResource&gt; GetAsync(class Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.GetAsync(Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeResource&gt;" Usage="Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.GetAsync (operations, resourceGroupName, factoryName, integrationRuntimeName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions/&lt;GetAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="integrationRuntimeName" Type="System.String" />
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
        <param name="integrationRuntimeName">
            統合ランタイムの名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            統合ランタイムを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetConnectionInfo">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeConnectionInfo GetConnectionInfo (this Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeConnectionInfo GetConnectionInfo(class Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.GetConnectionInfo(Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetConnectionInfo (operations As IIntegrationRuntimesOperations, resourceGroupName As String, factoryName As String, integrationRuntimeName As String) As IntegrationRuntimeConnectionInfo" />
      <MemberSignature Language="F#" Value="static member GetConnectionInfo : Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations * string * string * string -&gt; Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeConnectionInfo" Usage="Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.GetConnectionInfo (operations, resourceGroupName, factoryName, integrationRuntimeName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeConnectionInfo</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="integrationRuntimeName" Type="System.String" />
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
        <param name="integrationRuntimeName">
            統合ランタイムの名前。
            </param>
        <summary>
            オンプレミスの内部設置型のデータ ソースの資格情報を暗号化するための統合のランタイム接続情報を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetConnectionInfoAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeConnectionInfo&gt; GetConnectionInfoAsync (this Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeConnectionInfo&gt; GetConnectionInfoAsync(class Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.GetConnectionInfoAsync(Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetConnectionInfoAsync : Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeConnectionInfo&gt;" Usage="Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.GetConnectionInfoAsync (operations, resourceGroupName, factoryName, integrationRuntimeName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions/&lt;GetConnectionInfoAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeConnectionInfo&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="integrationRuntimeName" Type="System.String" />
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
        <param name="integrationRuntimeName">
            統合ランタイムの名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            オンプレミスの内部設置型のデータ ソースの資格情報を暗号化するための統合のランタイム接続情報を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMonitoringData">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeMonitoringData GetMonitoringData (this Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeMonitoringData GetMonitoringData(class Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.GetMonitoringData(Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetMonitoringData (operations As IIntegrationRuntimesOperations, resourceGroupName As String, factoryName As String, integrationRuntimeName As String) As IntegrationRuntimeMonitoringData" />
      <MemberSignature Language="F#" Value="static member GetMonitoringData : Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations * string * string * string -&gt; Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeMonitoringData" Usage="Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.GetMonitoringData (operations, resourceGroupName, factoryName, integrationRuntimeName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeMonitoringData</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="integrationRuntimeName" Type="System.String" />
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
        <param name="integrationRuntimeName">
            統合ランタイムの名前。
            </param>
        <summary>
            監視データをこの統合ランタイムの下にあるすべてのノードのモニターのデータを含む、統合ランタイムを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMonitoringDataAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeMonitoringData&gt; GetMonitoringDataAsync (this Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeMonitoringData&gt; GetMonitoringDataAsync(class Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.GetMonitoringDataAsync(Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetMonitoringDataAsync : Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeMonitoringData&gt;" Usage="Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.GetMonitoringDataAsync (operations, resourceGroupName, factoryName, integrationRuntimeName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions/&lt;GetMonitoringDataAsync&gt;d__27))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeMonitoringData&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="integrationRuntimeName" Type="System.String" />
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
        <param name="integrationRuntimeName">
            統合ランタイムの名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            監視データをこの統合ランタイムの下にあるすべてのノードのモニターのデータを含む、統合ランタイムを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetStatus">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeStatusResponse GetStatus (this Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeStatusResponse GetStatus(class Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.GetStatus(Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetStatus (operations As IIntegrationRuntimesOperations, resourceGroupName As String, factoryName As String, integrationRuntimeName As String) As IntegrationRuntimeStatusResponse" />
      <MemberSignature Language="F#" Value="static member GetStatus : Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations * string * string * string -&gt; Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeStatusResponse" Usage="Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.GetStatus (operations, resourceGroupName, factoryName, integrationRuntimeName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeStatusResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="integrationRuntimeName" Type="System.String" />
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
        <param name="integrationRuntimeName">
            統合ランタイムの名前。
            </param>
        <summary>
            統合ランタイムの詳細なステータス情報を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetStatusAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeStatusResponse&gt; GetStatusAsync (this Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeStatusResponse&gt; GetStatusAsync(class Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.GetStatusAsync(Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetStatusAsync : Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeStatusResponse&gt;" Usage="Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.GetStatusAsync (operations, resourceGroupName, factoryName, integrationRuntimeName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions/&lt;GetStatusAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeStatusResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="integrationRuntimeName" Type="System.String" />
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
        <param name="integrationRuntimeName">
            統合ランタイムの名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            統合ランタイムの詳細なステータス情報を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAuthKeys">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeAuthKeys ListAuthKeys (this Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeAuthKeys ListAuthKeys(class Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.ListAuthKeys(Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAuthKeys (operations As IIntegrationRuntimesOperations, resourceGroupName As String, factoryName As String, integrationRuntimeName As String) As IntegrationRuntimeAuthKeys" />
      <MemberSignature Language="F#" Value="static member ListAuthKeys : Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations * string * string * string -&gt; Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeAuthKeys" Usage="Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.ListAuthKeys (operations, resourceGroupName, factoryName, integrationRuntimeName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeAuthKeys</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="integrationRuntimeName" Type="System.String" />
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
        <param name="integrationRuntimeName">
            統合ランタイムの名前。
            </param>
        <summary>
            統合ランタイムの認証キーを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAuthKeysAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeAuthKeys&gt; ListAuthKeysAsync (this Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeAuthKeys&gt; ListAuthKeysAsync(class Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.ListAuthKeysAsync(Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAuthKeysAsync : Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeAuthKeys&gt;" Usage="Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.ListAuthKeysAsync (operations, resourceGroupName, factoryName, integrationRuntimeName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions/&lt;ListAuthKeysAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeAuthKeys&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="integrationRuntimeName" Type="System.String" />
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
        <param name="integrationRuntimeName">
            統合ランタイムの名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            統合ランタイムの認証キーを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByFactory">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeResource&gt; ListByFactory (this Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeResource&gt; ListByFactory(class Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.ListByFactory(Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByFactory (operations As IIntegrationRuntimesOperations, resourceGroupName As String, factoryName As String) As IPage(Of IntegrationRuntimeResource)" />
      <MemberSignature Language="F#" Value="static member ListByFactory : Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeResource&gt;" Usage="Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.ListByFactory (operations, resourceGroupName, factoryName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations" RefType="this" />
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
            統合のランタイムを一覧表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByFactoryAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeResource&gt;&gt; ListByFactoryAsync (this Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeResource&gt;&gt; ListByFactoryAsync(class Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.ListByFactoryAsync(Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByFactoryAsync : Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeResource&gt;&gt;" Usage="Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.ListByFactoryAsync (operations, resourceGroupName, factoryName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions/&lt;ListByFactoryAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations" RefType="this" />
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
            統合のランタイムを一覧表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByFactoryNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeResource&gt; ListByFactoryNext (this Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeResource&gt; ListByFactoryNext(class Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.ListByFactoryNext(Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByFactoryNext (operations As IIntegrationRuntimesOperations, nextPageLink As String) As IPage(Of IntegrationRuntimeResource)" />
      <MemberSignature Language="F#" Value="static member ListByFactoryNext : Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeResource&gt;" Usage="Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.ListByFactoryNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations" RefType="this" />
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
            統合のランタイムを一覧表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByFactoryNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeResource&gt;&gt; ListByFactoryNextAsync (this Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeResource&gt;&gt; ListByFactoryNextAsync(class Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.ListByFactoryNextAsync(Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByFactoryNextAsync : Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeResource&gt;&gt;" Usage="Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.ListByFactoryNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions/&lt;ListByFactoryNextAsync&gt;d__35))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations" RefType="this" />
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
            統合のランタイムを一覧表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegenerateAuthKey">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeAuthKeys RegenerateAuthKey (this Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName, Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeRegenerateKeyParameters regenerateKeyParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeAuthKeys RegenerateAuthKey(class Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName, class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeRegenerateKeyParameters regenerateKeyParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.RegenerateAuthKey(Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeRegenerateKeyParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function RegenerateAuthKey (operations As IIntegrationRuntimesOperations, resourceGroupName As String, factoryName As String, integrationRuntimeName As String, regenerateKeyParameters As IntegrationRuntimeRegenerateKeyParameters) As IntegrationRuntimeAuthKeys" />
      <MemberSignature Language="F#" Value="static member RegenerateAuthKey : Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations * string * string * string * Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeRegenerateKeyParameters -&gt; Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeAuthKeys" Usage="Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.RegenerateAuthKey (operations, resourceGroupName, factoryName, integrationRuntimeName, regenerateKeyParameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeAuthKeys</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="integrationRuntimeName" Type="System.String" />
        <Parameter Name="regenerateKeyParameters" Type="Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeRegenerateKeyParameters" />
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
        <param name="integrationRuntimeName">
            統合ランタイムの名前。
            </param>
        <param name="regenerateKeyParameters">
            統合ランタイム認証キーを再生成するためのパラメーターです。
            </param>
        <summary>
            認証キー、統合ランタイムを再生成します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegenerateAuthKeyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeAuthKeys&gt; RegenerateAuthKeyAsync (this Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName, Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeRegenerateKeyParameters regenerateKeyParameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeAuthKeys&gt; RegenerateAuthKeyAsync(class Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName, class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeRegenerateKeyParameters regenerateKeyParameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.RegenerateAuthKeyAsync(Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeRegenerateKeyParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RegenerateAuthKeyAsync : Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations * string * string * string * Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeRegenerateKeyParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeAuthKeys&gt;" Usage="Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.RegenerateAuthKeyAsync (operations, resourceGroupName, factoryName, integrationRuntimeName, regenerateKeyParameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions/&lt;RegenerateAuthKeyAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeAuthKeys&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="integrationRuntimeName" Type="System.String" />
        <Parameter Name="regenerateKeyParameters" Type="Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeRegenerateKeyParameters" />
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
        <param name="integrationRuntimeName">
            統合ランタイムの名前。
            </param>
        <param name="regenerateKeyParameters">
            統合ランタイム認証キーを再生成するためのパラメーターです。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            認証キー、統合ランタイムを再生成します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveNode">
      <MemberSignature Language="C#" Value="public static void RemoveNode (this Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName, Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeRemoveNodeRequest removeNodeParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void RemoveNode(class Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName, class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeRemoveNodeRequest removeNodeParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.RemoveNode(Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeRemoveNodeRequest)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub RemoveNode (operations As IIntegrationRuntimesOperations, resourceGroupName As String, factoryName As String, integrationRuntimeName As String, removeNodeParameters As IntegrationRuntimeRemoveNodeRequest)" />
      <MemberSignature Language="F#" Value="static member RemoveNode : Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations * string * string * string * Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeRemoveNodeRequest -&gt; unit" Usage="Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.RemoveNode (operations, resourceGroupName, factoryName, integrationRuntimeName, removeNodeParameters)" />
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
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="integrationRuntimeName" Type="System.String" />
        <Parameter Name="removeNodeParameters" Type="Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeRemoveNodeRequest" />
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
        <param name="integrationRuntimeName">
            統合ランタイムの名前。
            </param>
        <param name="removeNodeParameters">
            統合ランタイムから削除するノードの名前。
            </param>
        <summary>
            ノードは、統合ランタイムから削除します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveNodeAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task RemoveNodeAsync (this Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName, Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeRemoveNodeRequest removeNodeParameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task RemoveNodeAsync(class Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName, class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeRemoveNodeRequest removeNodeParameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.RemoveNodeAsync(Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeRemoveNodeRequest,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RemoveNodeAsync : Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations * string * string * string * Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeRemoveNodeRequest * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.RemoveNodeAsync (operations, resourceGroupName, factoryName, integrationRuntimeName, removeNodeParameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions/&lt;RemoveNodeAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="integrationRuntimeName" Type="System.String" />
        <Parameter Name="removeNodeParameters" Type="Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeRemoveNodeRequest" />
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
        <param name="integrationRuntimeName">
            統合ランタイムの名前。
            </param>
        <param name="removeNodeParameters">
            統合ランタイムから削除するノードの名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            ノードは、統合ランタイムから削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Start">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeStatusResponse Start (this Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeStatusResponse Start(class Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.Start(Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Start (operations As IIntegrationRuntimesOperations, resourceGroupName As String, factoryName As String, integrationRuntimeName As String) As IntegrationRuntimeStatusResponse" />
      <MemberSignature Language="F#" Value="static member Start : Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations * string * string * string -&gt; Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeStatusResponse" Usage="Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.Start (operations, resourceGroupName, factoryName, integrationRuntimeName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeStatusResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="integrationRuntimeName" Type="System.String" />
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
        <param name="integrationRuntimeName">
            統合ランタイムの名前。
            </param>
        <summary>
            ManagedReserved 型統合ランタイムを起動します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeStatusResponse&gt; StartAsync (this Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeStatusResponse&gt; StartAsync(class Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.StartAsync(Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member StartAsync : Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeStatusResponse&gt;" Usage="Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.StartAsync (operations, resourceGroupName, factoryName, integrationRuntimeName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions/&lt;StartAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeStatusResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="integrationRuntimeName" Type="System.String" />
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
        <param name="integrationRuntimeName">
            統合ランタイムの名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            ManagedReserved 型統合ランタイムを起動します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Stop">
      <MemberSignature Language="C#" Value="public static void Stop (this Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Stop(class Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.Stop(Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Stop (operations As IIntegrationRuntimesOperations, resourceGroupName As String, factoryName As String, integrationRuntimeName As String)" />
      <MemberSignature Language="F#" Value="static member Stop : Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.Stop (operations, resourceGroupName, factoryName, integrationRuntimeName)" />
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
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="integrationRuntimeName" Type="System.String" />
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
        <param name="integrationRuntimeName">
            統合ランタイムの名前。
            </param>
        <summary>
            ManagedReserved 型統合ランタイムを停止します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StopAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task StopAsync (this Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task StopAsync(class Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.StopAsync(Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member StopAsync : Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.StopAsync (operations, resourceGroupName, factoryName, integrationRuntimeName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions/&lt;StopAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="integrationRuntimeName" Type="System.String" />
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
        <param name="integrationRuntimeName">
            統合ランタイムの名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            ManagedReserved 型統合ランタイムを停止します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SyncCredentials">
      <MemberSignature Language="C#" Value="public static void SyncCredentials (this Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void SyncCredentials(class Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.SyncCredentials(Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub SyncCredentials (operations As IIntegrationRuntimesOperations, resourceGroupName As String, factoryName As String, integrationRuntimeName As String)" />
      <MemberSignature Language="F#" Value="static member SyncCredentials : Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.SyncCredentials (operations, resourceGroupName, factoryName, integrationRuntimeName)" />
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
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="integrationRuntimeName" Type="System.String" />
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
        <param name="integrationRuntimeName">
            統合ランタイムの名前。
            </param>
        <summary>
            強制的に、統合ランタイム ノードでの資格情報を同期するために、統合ランタイムと、このディスパッチャー ノードで利用できるすべての worker ノードの間で資格情報は上書きされます。 最新の資格情報のバックアップ ファイルがある場合手動で (推奨)、この API を直接使用するよりも自己ホスト型の統合ランタイム ノードにインポートする必要があります。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SyncCredentialsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task SyncCredentialsAsync (this Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task SyncCredentialsAsync(class Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.SyncCredentialsAsync(Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member SyncCredentialsAsync : Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.SyncCredentialsAsync (operations, resourceGroupName, factoryName, integrationRuntimeName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions/&lt;SyncCredentialsAsync&gt;d__25))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="integrationRuntimeName" Type="System.String" />
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
        <param name="integrationRuntimeName">
            統合ランタイムの名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            強制的に、統合ランタイム ノードでの資格情報を同期するために、統合ランタイムと、このディスパッチャー ノードで利用できるすべての worker ノードの間で資格情報は上書きされます。 最新の資格情報のバックアップ ファイルがある場合手動で (推奨)、この API を直接使用するよりも自己ホスト型の統合ランタイム ノードにインポートする必要があります。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeStatusResponse Update (this Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName, Microsoft.Azure.Management.DataFactory.Models.UpdateIntegrationRuntimeRequest updateIntegrationRuntimeRequest);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeStatusResponse Update(class Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName, class Microsoft.Azure.Management.DataFactory.Models.UpdateIntegrationRuntimeRequest updateIntegrationRuntimeRequest) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.Update(Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataFactory.Models.UpdateIntegrationRuntimeRequest)" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations * string * string * string * Microsoft.Azure.Management.DataFactory.Models.UpdateIntegrationRuntimeRequest -&gt; Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeStatusResponse" Usage="Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.Update (operations, resourceGroupName, factoryName, integrationRuntimeName, updateIntegrationRuntimeRequest)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeStatusResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="integrationRuntimeName" Type="System.String" />
        <Parameter Name="updateIntegrationRuntimeRequest" Type="Microsoft.Azure.Management.DataFactory.Models.UpdateIntegrationRuntimeRequest" />
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
        <param name="integrationRuntimeName">
            統合ランタイムの名前。
            </param>
        <param name="updateIntegrationRuntimeRequest">
            統合ランタイムを更新するためのパラメーターです。
            </param>
        <summary>
            統合ランタイムを更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeStatusResponse&gt; UpdateAsync (this Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName, Microsoft.Azure.Management.DataFactory.Models.UpdateIntegrationRuntimeRequest updateIntegrationRuntimeRequest, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeStatusResponse&gt; UpdateAsync(class Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName, class Microsoft.Azure.Management.DataFactory.Models.UpdateIntegrationRuntimeRequest updateIntegrationRuntimeRequest, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataFactory.Models.UpdateIntegrationRuntimeRequest,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations * string * string * string * Microsoft.Azure.Management.DataFactory.Models.UpdateIntegrationRuntimeRequest * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeStatusResponse&gt;" Usage="Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.UpdateAsync (operations, resourceGroupName, factoryName, integrationRuntimeName, updateIntegrationRuntimeRequest, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions/&lt;UpdateAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeStatusResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="integrationRuntimeName" Type="System.String" />
        <Parameter Name="updateIntegrationRuntimeRequest" Type="Microsoft.Azure.Management.DataFactory.Models.UpdateIntegrationRuntimeRequest" />
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
        <param name="integrationRuntimeName">
            統合ランタイムの名前。
            </param>
        <param name="updateIntegrationRuntimeRequest">
            統合ランタイムを更新するためのパラメーターです。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            統合ランタイムを更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Upgrade">
      <MemberSignature Language="C#" Value="public static void Upgrade (this Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Upgrade(class Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.Upgrade(Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Upgrade (operations As IIntegrationRuntimesOperations, resourceGroupName As String, factoryName As String, integrationRuntimeName As String)" />
      <MemberSignature Language="F#" Value="static member Upgrade : Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.Upgrade (operations, resourceGroupName, factoryName, integrationRuntimeName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="integrationRuntimeName" Type="System.String" />
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
        <param name="integrationRuntimeName">
            統合ランタイムの名前。
            </param>
        <summary>
            可用性の場合、最新バージョンに自己ホスト型の統合ランタイムをアップグレードします。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradeAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task UpgradeAsync (this Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task UpgradeAsync(class Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.UpgradeAsync(Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpgradeAsync : Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.UpgradeAsync (operations, resourceGroupName, factoryName, integrationRuntimeName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions/&lt;UpgradeAsync&gt;d__29))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="integrationRuntimeName" Type="System.String" />
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
        <param name="integrationRuntimeName">
            統合ランタイムの名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            可用性の場合、最新バージョンに自己ホスト型の統合ランタイムをアップグレードします。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>