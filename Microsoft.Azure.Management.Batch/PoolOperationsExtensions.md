<Type Name="PoolOperationsExtensions" FullName="Microsoft.Azure.Management.Batch.PoolOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class PoolOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit PoolOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Batch.PoolOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module PoolOperationsExtensions" />
  <TypeSignature Language="F#" Value="type PoolOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            PoolOperations の拡張メソッド。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Batch.Models.Pool BeginCreate (this Microsoft.Azure.Management.Batch.IPoolOperations operations, string resourceGroupName, string accountName, string poolName, Microsoft.Azure.Management.Batch.Models.Pool parameters, string ifMatch = null, string ifNoneMatch = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Batch.Models.Pool BeginCreate(class Microsoft.Azure.Management.Batch.IPoolOperations operations, string resourceGroupName, string accountName, string poolName, class Microsoft.Azure.Management.Batch.Models.Pool parameters, string ifMatch, string ifNoneMatch) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.PoolOperationsExtensions.BeginCreate(Microsoft.Azure.Management.Batch.IPoolOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Batch.Models.Pool,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreate (operations As IPoolOperations, resourceGroupName As String, accountName As String, poolName As String, parameters As Pool, Optional ifMatch As String = null, Optional ifNoneMatch As String = null) As Pool" />
      <MemberSignature Language="F#" Value="static member BeginCreate : Microsoft.Azure.Management.Batch.IPoolOperations * string * string * string * Microsoft.Azure.Management.Batch.Models.Pool * string * string -&gt; Microsoft.Azure.Management.Batch.Models.Pool" Usage="Microsoft.Azure.Management.Batch.PoolOperationsExtensions.BeginCreate (operations, resourceGroupName, accountName, poolName, parameters, ifMatch, ifNoneMatch)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.Pool</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.IPoolOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="poolName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Batch.Models.Pool" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="ifNoneMatch" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Batch アカウントが含まれているリソース グループの名前。
            </param>
        <param name="accountName">
            Batch アカウントの名前。
            </param>
        <param name="poolName">
            プール名です。 これは、アカウント内で一意でなければなりません。
            </param>
        <param name="parameters">
            プールの作成に追加のパラメーターです。
            </param>
        <param name="ifMatch">
            更新するプールのエンティティの状態 (ETag) のバージョン。 値"*"、プールが既に存在する場合にのみ、操作を適用するために使用できます。 省略した場合、この操作常に使用されます。
            </param>
        <param name="ifNoneMatch">
            設定 ' *'、新しいプールを作成するが、既存のプールの更新を防ぐために使用できるようにします。 その他の値は無視されます。
            </param>
        <summary>
            指定されたアカウント内の新しいプールを作成します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.Pool&gt; BeginCreateAsync (this Microsoft.Azure.Management.Batch.IPoolOperations operations, string resourceGroupName, string accountName, string poolName, Microsoft.Azure.Management.Batch.Models.Pool parameters, string ifMatch = null, string ifNoneMatch = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Batch.Models.Pool&gt; BeginCreateAsync(class Microsoft.Azure.Management.Batch.IPoolOperations operations, string resourceGroupName, string accountName, string poolName, class Microsoft.Azure.Management.Batch.Models.Pool parameters, string ifMatch, string ifNoneMatch, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.PoolOperationsExtensions.BeginCreateAsync(Microsoft.Azure.Management.Batch.IPoolOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Batch.Models.Pool,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateAsync : Microsoft.Azure.Management.Batch.IPoolOperations * string * string * string * Microsoft.Azure.Management.Batch.Models.Pool * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.Pool&gt;" Usage="Microsoft.Azure.Management.Batch.PoolOperationsExtensions.BeginCreateAsync (operations, resourceGroupName, accountName, poolName, parameters, ifMatch, ifNoneMatch, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.PoolOperationsExtensions/&lt;BeginCreateAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.Pool&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.IPoolOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="poolName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Batch.Models.Pool" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="ifNoneMatch" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Batch アカウントが含まれているリソース グループの名前。
            </param>
        <param name="accountName">
            Batch アカウントの名前。
            </param>
        <param name="poolName">
            プール名です。 これは、アカウント内で一意でなければなりません。
            </param>
        <param name="parameters">
            プールの作成に追加のパラメーターです。
            </param>
        <param name="ifMatch">
            更新するプールのエンティティの状態 (ETag) のバージョン。 値"*"、プールが既に存在する場合にのみ、操作を適用するために使用できます。 省略した場合、この操作常に使用されます。
            </param>
        <param name="ifNoneMatch">
            設定 ' *'、新しいプールを作成するが、既存のプールの更新を防ぐために使用できるようにします。 その他の値は無視されます。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定されたアカウント内の新しいプールを作成します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Batch.Models.PoolDeleteHeaders BeginDelete (this Microsoft.Azure.Management.Batch.IPoolOperations operations, string resourceGroupName, string accountName, string poolName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Batch.Models.PoolDeleteHeaders BeginDelete(class Microsoft.Azure.Management.Batch.IPoolOperations operations, string resourceGroupName, string accountName, string poolName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.PoolOperationsExtensions.BeginDelete(Microsoft.Azure.Management.Batch.IPoolOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginDelete (operations As IPoolOperations, resourceGroupName As String, accountName As String, poolName As String) As PoolDeleteHeaders" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.Batch.IPoolOperations * string * string * string -&gt; Microsoft.Azure.Management.Batch.Models.PoolDeleteHeaders" Usage="Microsoft.Azure.Management.Batch.PoolOperationsExtensions.BeginDelete (operations, resourceGroupName, accountName, poolName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.PoolDeleteHeaders</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.IPoolOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="poolName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Batch アカウントが含まれているリソース グループの名前。
            </param>
        <param name="accountName">
            Batch アカウントの名前。
            </param>
        <param name="poolName">
            プール名です。 これは、アカウント内で一意でなければなりません。
            </param>
        <summary>
            指定したプールを削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.PoolDeleteHeaders&gt; BeginDeleteAsync (this Microsoft.Azure.Management.Batch.IPoolOperations operations, string resourceGroupName, string accountName, string poolName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Batch.Models.PoolDeleteHeaders&gt; BeginDeleteAsync(class Microsoft.Azure.Management.Batch.IPoolOperations operations, string resourceGroupName, string accountName, string poolName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.PoolOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Batch.IPoolOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Batch.IPoolOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.PoolDeleteHeaders&gt;" Usage="Microsoft.Azure.Management.Batch.PoolOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, accountName, poolName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.PoolOperationsExtensions/&lt;BeginDeleteAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.PoolDeleteHeaders&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.IPoolOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="poolName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Batch アカウントが含まれているリソース グループの名前。
            </param>
        <param name="accountName">
            Batch アカウントの名前。
            </param>
        <param name="poolName">
            プール名です。 これは、アカウント内で一意でなければなりません。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定したプールを削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Batch.Models.Pool Create (this Microsoft.Azure.Management.Batch.IPoolOperations operations, string resourceGroupName, string accountName, string poolName, Microsoft.Azure.Management.Batch.Models.Pool parameters, string ifMatch = null, string ifNoneMatch = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Batch.Models.Pool Create(class Microsoft.Azure.Management.Batch.IPoolOperations operations, string resourceGroupName, string accountName, string poolName, class Microsoft.Azure.Management.Batch.Models.Pool parameters, string ifMatch, string ifNoneMatch) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.PoolOperationsExtensions.Create(Microsoft.Azure.Management.Batch.IPoolOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Batch.Models.Pool,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Create (operations As IPoolOperations, resourceGroupName As String, accountName As String, poolName As String, parameters As Pool, Optional ifMatch As String = null, Optional ifNoneMatch As String = null) As Pool" />
      <MemberSignature Language="F#" Value="static member Create : Microsoft.Azure.Management.Batch.IPoolOperations * string * string * string * Microsoft.Azure.Management.Batch.Models.Pool * string * string -&gt; Microsoft.Azure.Management.Batch.Models.Pool" Usage="Microsoft.Azure.Management.Batch.PoolOperationsExtensions.Create (operations, resourceGroupName, accountName, poolName, parameters, ifMatch, ifNoneMatch)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.Pool</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.IPoolOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="poolName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Batch.Models.Pool" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="ifNoneMatch" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Batch アカウントが含まれているリソース グループの名前。
            </param>
        <param name="accountName">
            Batch アカウントの名前。
            </param>
        <param name="poolName">
            プール名です。 これは、アカウント内で一意でなければなりません。
            </param>
        <param name="parameters">
            プールの作成に追加のパラメーターです。
            </param>
        <param name="ifMatch">
            更新するプールのエンティティの状態 (ETag) のバージョン。 値"*"、プールが既に存在する場合にのみ、操作を適用するために使用できます。 省略した場合、この操作常に使用されます。
            </param>
        <param name="ifNoneMatch">
            設定 ' *'、新しいプールを作成するが、既存のプールの更新を防ぐために使用できるようにします。 その他の値は無視されます。
            </param>
        <summary>
            指定されたアカウント内の新しいプールを作成します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.Pool&gt; CreateAsync (this Microsoft.Azure.Management.Batch.IPoolOperations operations, string resourceGroupName, string accountName, string poolName, Microsoft.Azure.Management.Batch.Models.Pool parameters, string ifMatch = null, string ifNoneMatch = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Batch.Models.Pool&gt; CreateAsync(class Microsoft.Azure.Management.Batch.IPoolOperations operations, string resourceGroupName, string accountName, string poolName, class Microsoft.Azure.Management.Batch.Models.Pool parameters, string ifMatch, string ifNoneMatch, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.PoolOperationsExtensions.CreateAsync(Microsoft.Azure.Management.Batch.IPoolOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Batch.Models.Pool,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : Microsoft.Azure.Management.Batch.IPoolOperations * string * string * string * Microsoft.Azure.Management.Batch.Models.Pool * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.Pool&gt;" Usage="Microsoft.Azure.Management.Batch.PoolOperationsExtensions.CreateAsync (operations, resourceGroupName, accountName, poolName, parameters, ifMatch, ifNoneMatch, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.PoolOperationsExtensions/&lt;CreateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.Pool&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.IPoolOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="poolName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Batch.Models.Pool" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="ifNoneMatch" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Batch アカウントが含まれているリソース グループの名前。
            </param>
        <param name="accountName">
            Batch アカウントの名前。
            </param>
        <param name="poolName">
            プール名です。 これは、アカウント内で一意でなければなりません。
            </param>
        <param name="parameters">
            プールの作成に追加のパラメーターです。
            </param>
        <param name="ifMatch">
            更新するプールのエンティティの状態 (ETag) のバージョン。 値"*"、プールが既に存在する場合にのみ、操作を適用するために使用できます。 省略した場合、この操作常に使用されます。
            </param>
        <param name="ifNoneMatch">
            設定 ' *'、新しいプールを作成するが、既存のプールの更新を防ぐために使用できるようにします。 その他の値は無視されます。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定されたアカウント内の新しいプールを作成します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Batch.Models.PoolDeleteHeaders Delete (this Microsoft.Azure.Management.Batch.IPoolOperations operations, string resourceGroupName, string accountName, string poolName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Batch.Models.PoolDeleteHeaders Delete(class Microsoft.Azure.Management.Batch.IPoolOperations operations, string resourceGroupName, string accountName, string poolName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.PoolOperationsExtensions.Delete(Microsoft.Azure.Management.Batch.IPoolOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Delete (operations As IPoolOperations, resourceGroupName As String, accountName As String, poolName As String) As PoolDeleteHeaders" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Batch.IPoolOperations * string * string * string -&gt; Microsoft.Azure.Management.Batch.Models.PoolDeleteHeaders" Usage="Microsoft.Azure.Management.Batch.PoolOperationsExtensions.Delete (operations, resourceGroupName, accountName, poolName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.PoolDeleteHeaders</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.IPoolOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="poolName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Batch アカウントが含まれているリソース グループの名前。
            </param>
        <param name="accountName">
            Batch アカウントの名前。
            </param>
        <param name="poolName">
            プール名です。 これは、アカウント内で一意でなければなりません。
            </param>
        <summary>
            指定したプールを削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.PoolDeleteHeaders&gt; DeleteAsync (this Microsoft.Azure.Management.Batch.IPoolOperations operations, string resourceGroupName, string accountName, string poolName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Batch.Models.PoolDeleteHeaders&gt; DeleteAsync(class Microsoft.Azure.Management.Batch.IPoolOperations operations, string resourceGroupName, string accountName, string poolName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.PoolOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Batch.IPoolOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Batch.IPoolOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.PoolDeleteHeaders&gt;" Usage="Microsoft.Azure.Management.Batch.PoolOperationsExtensions.DeleteAsync (operations, resourceGroupName, accountName, poolName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.PoolOperationsExtensions/&lt;DeleteAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.PoolDeleteHeaders&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.IPoolOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="poolName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Batch アカウントが含まれているリソース グループの名前。
            </param>
        <param name="accountName">
            Batch アカウントの名前。
            </param>
        <param name="poolName">
            プール名です。 これは、アカウント内で一意でなければなりません。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定したプールを削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisableAutoScale">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Batch.Models.Pool DisableAutoScale (this Microsoft.Azure.Management.Batch.IPoolOperations operations, string resourceGroupName, string accountName, string poolName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Batch.Models.Pool DisableAutoScale(class Microsoft.Azure.Management.Batch.IPoolOperations operations, string resourceGroupName, string accountName, string poolName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.PoolOperationsExtensions.DisableAutoScale(Microsoft.Azure.Management.Batch.IPoolOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function DisableAutoScale (operations As IPoolOperations, resourceGroupName As String, accountName As String, poolName As String) As Pool" />
      <MemberSignature Language="F#" Value="static member DisableAutoScale : Microsoft.Azure.Management.Batch.IPoolOperations * string * string * string -&gt; Microsoft.Azure.Management.Batch.Models.Pool" Usage="Microsoft.Azure.Management.Batch.PoolOperationsExtensions.DisableAutoScale (operations, resourceGroupName, accountName, poolName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.Pool</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.IPoolOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="poolName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Batch アカウントが含まれているリソース グループの名前。
            </param>
        <param name="accountName">
            Batch アカウントの名前。
            </param>
        <param name="poolName">
            プール名です。 これは、アカウント内で一意でなければなりません。
            </param>
        <summary>
            プールの自動スケーリングを無効にします。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisableAutoScaleAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.Pool&gt; DisableAutoScaleAsync (this Microsoft.Azure.Management.Batch.IPoolOperations operations, string resourceGroupName, string accountName, string poolName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Batch.Models.Pool&gt; DisableAutoScaleAsync(class Microsoft.Azure.Management.Batch.IPoolOperations operations, string resourceGroupName, string accountName, string poolName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.PoolOperationsExtensions.DisableAutoScaleAsync(Microsoft.Azure.Management.Batch.IPoolOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DisableAutoScaleAsync : Microsoft.Azure.Management.Batch.IPoolOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.Pool&gt;" Usage="Microsoft.Azure.Management.Batch.PoolOperationsExtensions.DisableAutoScaleAsync (operations, resourceGroupName, accountName, poolName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.PoolOperationsExtensions/&lt;DisableAutoScaleAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.Pool&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.IPoolOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="poolName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Batch アカウントが含まれているリソース グループの名前。
            </param>
        <param name="accountName">
            Batch アカウントの名前。
            </param>
        <param name="poolName">
            プール名です。 これは、アカウント内で一意でなければなりません。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            プールの自動スケーリングを無効にします。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Batch.Models.Pool Get (this Microsoft.Azure.Management.Batch.IPoolOperations operations, string resourceGroupName, string accountName, string poolName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Batch.Models.Pool Get(class Microsoft.Azure.Management.Batch.IPoolOperations operations, string resourceGroupName, string accountName, string poolName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.PoolOperationsExtensions.Get(Microsoft.Azure.Management.Batch.IPoolOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IPoolOperations, resourceGroupName As String, accountName As String, poolName As String) As Pool" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Batch.IPoolOperations * string * string * string -&gt; Microsoft.Azure.Management.Batch.Models.Pool" Usage="Microsoft.Azure.Management.Batch.PoolOperationsExtensions.Get (operations, resourceGroupName, accountName, poolName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.Pool</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.IPoolOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="poolName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Batch アカウントが含まれているリソース グループの名前。
            </param>
        <param name="accountName">
            Batch アカウントの名前。
            </param>
        <param name="poolName">
            プール名です。 これは、アカウント内で一意でなければなりません。
            </param>
        <summary>
            指定したプールに関する情報を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.Pool&gt; GetAsync (this Microsoft.Azure.Management.Batch.IPoolOperations operations, string resourceGroupName, string accountName, string poolName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Batch.Models.Pool&gt; GetAsync(class Microsoft.Azure.Management.Batch.IPoolOperations operations, string resourceGroupName, string accountName, string poolName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.PoolOperationsExtensions.GetAsync(Microsoft.Azure.Management.Batch.IPoolOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Batch.IPoolOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.Pool&gt;" Usage="Microsoft.Azure.Management.Batch.PoolOperationsExtensions.GetAsync (operations, resourceGroupName, accountName, poolName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.PoolOperationsExtensions/&lt;GetAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.Pool&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.IPoolOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="poolName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Batch アカウントが含まれているリソース グループの名前。
            </param>
        <param name="accountName">
            Batch アカウントの名前。
            </param>
        <param name="poolName">
            プール名です。 これは、アカウント内で一意でなければなりません。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定したプールに関する情報を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByBatchAccount">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.Pool&gt; ListByBatchAccount (this Microsoft.Azure.Management.Batch.IPoolOperations operations, string resourceGroupName, string accountName, Nullable&lt;int&gt; maxresults = null, string select = null, string filter = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Batch.Models.Pool&gt; ListByBatchAccount(class Microsoft.Azure.Management.Batch.IPoolOperations operations, string resourceGroupName, string accountName, valuetype System.Nullable`1&lt;int32&gt; maxresults, string select, string filter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.PoolOperationsExtensions.ListByBatchAccount(Microsoft.Azure.Management.Batch.IPoolOperations,System.String,System.String,System.Nullable{System.Int32},System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByBatchAccount (operations As IPoolOperations, resourceGroupName As String, accountName As String, Optional maxresults As Nullable(Of Integer) = null, Optional select As String = null, Optional filter As String = null) As IPage(Of Pool)" />
      <MemberSignature Language="F#" Value="static member ListByBatchAccount : Microsoft.Azure.Management.Batch.IPoolOperations * string * string * Nullable&lt;int&gt; * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.Pool&gt;" Usage="Microsoft.Azure.Management.Batch.PoolOperationsExtensions.ListByBatchAccount (operations, resourceGroupName, accountName, maxresults, select, filter)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.Pool&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.IPoolOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="maxresults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="filter" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
             この拡張メソッドの操作のグループです。
             </param>
        <param name="resourceGroupName">
             Batch アカウントが含まれているリソース グループの名前。
             </param>
        <param name="accountName">
             Batch アカウントの名前。
             </param>
        <param name="maxresults">
             応答で返されるアイテムの最大数。
             </param>
        <param name="select">
             コンマ区切りのプロパティの一覧を返す必要があります。 例:"のプロパティ/provisioningState"です。 のみの上位レベル のプロパティのプロパティ/選択に対して有効です。
             </param>
        <param name="filter">
             OData フィルター式です。 フィルター処理の有効なプロパティは次のとおりです。
            
             プロパティ/allocationState プロパティ/allocationStateTransitionTime プロパティ/creationTime プロパティ/provisioningState プロパティ/provisioningStateTransitionTime プロパティ/lastModified プロパティ/vmSize プロパティの名前/interNodeCommunication 自動スケールのプロパティ/scaleSettings/プロパティ/scaleSettings/fixedScale
             </param>
        <summary>
             指定されたアカウント内のプールのすべての一覧を表示します。
             </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByBatchAccountAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.Pool&gt;&gt; ListByBatchAccountAsync (this Microsoft.Azure.Management.Batch.IPoolOperations operations, string resourceGroupName, string accountName, Nullable&lt;int&gt; maxresults = null, string select = null, string filter = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Batch.Models.Pool&gt;&gt; ListByBatchAccountAsync(class Microsoft.Azure.Management.Batch.IPoolOperations operations, string resourceGroupName, string accountName, valuetype System.Nullable`1&lt;int32&gt; maxresults, string select, string filter, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.PoolOperationsExtensions.ListByBatchAccountAsync(Microsoft.Azure.Management.Batch.IPoolOperations,System.String,System.String,System.Nullable{System.Int32},System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByBatchAccountAsync : Microsoft.Azure.Management.Batch.IPoolOperations * string * string * Nullable&lt;int&gt; * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.Pool&gt;&gt;" Usage="Microsoft.Azure.Management.Batch.PoolOperationsExtensions.ListByBatchAccountAsync (operations, resourceGroupName, accountName, maxresults, select, filter, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.PoolOperationsExtensions/&lt;ListByBatchAccountAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.Pool&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.IPoolOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="maxresults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="filter" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
             この拡張メソッドの操作のグループです。
             </param>
        <param name="resourceGroupName">
             Batch アカウントが含まれているリソース グループの名前。
             </param>
        <param name="accountName">
             Batch アカウントの名前。
             </param>
        <param name="maxresults">
             応答で返されるアイテムの最大数。
             </param>
        <param name="select">
             コンマ区切りのプロパティの一覧を返す必要があります。 例:"のプロパティ/provisioningState"です。 のみの上位レベル のプロパティのプロパティ/選択に対して有効です。
             </param>
        <param name="filter">
             OData フィルター式です。 フィルター処理の有効なプロパティは次のとおりです。
            
             プロパティ/allocationState プロパティ/allocationStateTransitionTime プロパティ/creationTime プロパティ/provisioningState プロパティ/provisioningStateTransitionTime プロパティ/lastModified プロパティ/vmSize プロパティの名前/interNodeCommunication 自動スケールのプロパティ/scaleSettings/プロパティ/scaleSettings/fixedScale
             </param>
        <param name="cancellationToken">
             キャンセル トークン。
             </param>
        <summary>
             指定されたアカウント内のプールのすべての一覧を表示します。
             </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByBatchAccountNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.Pool&gt; ListByBatchAccountNext (this Microsoft.Azure.Management.Batch.IPoolOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Batch.Models.Pool&gt; ListByBatchAccountNext(class Microsoft.Azure.Management.Batch.IPoolOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.PoolOperationsExtensions.ListByBatchAccountNext(Microsoft.Azure.Management.Batch.IPoolOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByBatchAccountNext (operations As IPoolOperations, nextPageLink As String) As IPage(Of Pool)" />
      <MemberSignature Language="F#" Value="static member ListByBatchAccountNext : Microsoft.Azure.Management.Batch.IPoolOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.Pool&gt;" Usage="Microsoft.Azure.Management.Batch.PoolOperationsExtensions.ListByBatchAccountNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.Pool&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.IPoolOperations" RefType="this" />
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
            指定されたアカウント内のプールのすべての一覧を表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByBatchAccountNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.Pool&gt;&gt; ListByBatchAccountNextAsync (this Microsoft.Azure.Management.Batch.IPoolOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Batch.Models.Pool&gt;&gt; ListByBatchAccountNextAsync(class Microsoft.Azure.Management.Batch.IPoolOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.PoolOperationsExtensions.ListByBatchAccountNextAsync(Microsoft.Azure.Management.Batch.IPoolOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByBatchAccountNextAsync : Microsoft.Azure.Management.Batch.IPoolOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.Pool&gt;&gt;" Usage="Microsoft.Azure.Management.Batch.PoolOperationsExtensions.ListByBatchAccountNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.PoolOperationsExtensions/&lt;ListByBatchAccountNextAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.Pool&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.IPoolOperations" RefType="this" />
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
            指定されたアカウント内のプールのすべての一覧を表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StopResize">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Batch.Models.Pool StopResize (this Microsoft.Azure.Management.Batch.IPoolOperations operations, string resourceGroupName, string accountName, string poolName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Batch.Models.Pool StopResize(class Microsoft.Azure.Management.Batch.IPoolOperations operations, string resourceGroupName, string accountName, string poolName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.PoolOperationsExtensions.StopResize(Microsoft.Azure.Management.Batch.IPoolOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function StopResize (operations As IPoolOperations, resourceGroupName As String, accountName As String, poolName As String) As Pool" />
      <MemberSignature Language="F#" Value="static member StopResize : Microsoft.Azure.Management.Batch.IPoolOperations * string * string * string -&gt; Microsoft.Azure.Management.Batch.Models.Pool" Usage="Microsoft.Azure.Management.Batch.PoolOperationsExtensions.StopResize (operations, resourceGroupName, accountName, poolName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.Pool</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.IPoolOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="poolName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Batch アカウントが含まれているリソース グループの名前。
            </param>
        <param name="accountName">
            Batch アカウントの名前。
            </param>
        <param name="poolName">
            プール名です。 これは、アカウント内で一意でなければなりません。
            </param>
        <summary>
            継続的な停止のサイズ変更、プールに操作します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            プール サイズ変更操作の前に以前の状態は元に戻りません。 行われるさらなる変更だけが停止され、プールが、現在の状態を維持します。 停止後、プールが停止操作が完了するとではノードの数に安定します。 プール割り当て状態は、停止操作中は停止してから、安定したに最初に変更します。 サイズ変更操作で、明示的なサイズ変更プール要求である必要はありません。この API は、作成時に、プールの初期サイズ設定を停止するようにも使用できます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="StopResizeAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.Pool&gt; StopResizeAsync (this Microsoft.Azure.Management.Batch.IPoolOperations operations, string resourceGroupName, string accountName, string poolName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Batch.Models.Pool&gt; StopResizeAsync(class Microsoft.Azure.Management.Batch.IPoolOperations operations, string resourceGroupName, string accountName, string poolName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.PoolOperationsExtensions.StopResizeAsync(Microsoft.Azure.Management.Batch.IPoolOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member StopResizeAsync : Microsoft.Azure.Management.Batch.IPoolOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.Pool&gt;" Usage="Microsoft.Azure.Management.Batch.PoolOperationsExtensions.StopResizeAsync (operations, resourceGroupName, accountName, poolName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.PoolOperationsExtensions/&lt;StopResizeAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.Pool&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.IPoolOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="poolName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Batch アカウントが含まれているリソース グループの名前。
            </param>
        <param name="accountName">
            Batch アカウントの名前。
            </param>
        <param name="poolName">
            プール名です。 これは、アカウント内で一意でなければなりません。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            継続的な停止のサイズ変更、プールに操作します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            プール サイズ変更操作の前に以前の状態は元に戻りません。 行われるさらなる変更だけが停止され、プールが、現在の状態を維持します。 停止後、プールが停止操作が完了するとではノードの数に安定します。 プール割り当て状態は、停止操作中は停止してから、安定したに最初に変更します。 サイズ変更操作で、明示的なサイズ変更プール要求である必要はありません。この API は、作成時に、プールの初期サイズ設定を停止するようにも使用できます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Batch.Models.Pool Update (this Microsoft.Azure.Management.Batch.IPoolOperations operations, string resourceGroupName, string accountName, string poolName, Microsoft.Azure.Management.Batch.Models.Pool parameters, string ifMatch = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Batch.Models.Pool Update(class Microsoft.Azure.Management.Batch.IPoolOperations operations, string resourceGroupName, string accountName, string poolName, class Microsoft.Azure.Management.Batch.Models.Pool parameters, string ifMatch) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.PoolOperationsExtensions.Update(Microsoft.Azure.Management.Batch.IPoolOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Batch.Models.Pool,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Update (operations As IPoolOperations, resourceGroupName As String, accountName As String, poolName As String, parameters As Pool, Optional ifMatch As String = null) As Pool" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Management.Batch.IPoolOperations * string * string * string * Microsoft.Azure.Management.Batch.Models.Pool * string -&gt; Microsoft.Azure.Management.Batch.Models.Pool" Usage="Microsoft.Azure.Management.Batch.PoolOperationsExtensions.Update (operations, resourceGroupName, accountName, poolName, parameters, ifMatch)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.Pool</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.IPoolOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="poolName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Batch.Models.Pool" />
        <Parameter Name="ifMatch" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Batch アカウントが含まれているリソース グループの名前。
            </param>
        <param name="accountName">
            Batch アカウントの名前。
            </param>
        <param name="poolName">
            プール名です。 これは、アカウント内で一意でなければなりません。
            </param>
        <param name="parameters">
            更新する必要があるプールのプロパティです。 指定されたプロパティが更新されます、指定されていない任意のプロパティは変更されません。
            </param>
        <param name="ifMatch">
            更新するプールのエンティティの状態 (ETag) のバージョン。 この値を省略するかに設定することができます"*"を無条件で操作を適用します。
            </param>
        <summary>
            既存のプールのプロパティを更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.Pool&gt; UpdateAsync (this Microsoft.Azure.Management.Batch.IPoolOperations operations, string resourceGroupName, string accountName, string poolName, Microsoft.Azure.Management.Batch.Models.Pool parameters, string ifMatch = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Batch.Models.Pool&gt; UpdateAsync(class Microsoft.Azure.Management.Batch.IPoolOperations operations, string resourceGroupName, string accountName, string poolName, class Microsoft.Azure.Management.Batch.Models.Pool parameters, string ifMatch, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.PoolOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.Batch.IPoolOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Batch.Models.Pool,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.Batch.IPoolOperations * string * string * string * Microsoft.Azure.Management.Batch.Models.Pool * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.Pool&gt;" Usage="Microsoft.Azure.Management.Batch.PoolOperationsExtensions.UpdateAsync (operations, resourceGroupName, accountName, poolName, parameters, ifMatch, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.PoolOperationsExtensions/&lt;UpdateAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.Pool&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.IPoolOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="poolName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Batch.Models.Pool" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Batch アカウントが含まれているリソース グループの名前。
            </param>
        <param name="accountName">
            Batch アカウントの名前。
            </param>
        <param name="poolName">
            プール名です。 これは、アカウント内で一意でなければなりません。
            </param>
        <param name="parameters">
            更新する必要があるプールのプロパティです。 指定されたプロパティが更新されます、指定されていない任意のプロパティは変更されません。
            </param>
        <param name="ifMatch">
            更新するプールのエンティティの状態 (ETag) のバージョン。 この値を省略するかに設定することができます"*"を無条件で操作を適用します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            既存のプールのプロパティを更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>