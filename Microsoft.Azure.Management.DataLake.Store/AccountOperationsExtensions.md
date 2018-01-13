<Type Name="AccountOperationsExtensions" FullName="Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class AccountOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit AccountOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module AccountOperationsExtensions" />
  <TypeSignature Language="F#" Value="type AccountOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            AccountOperations の拡張メソッド。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount BeginCreate (this Microsoft.Azure.Management.DataLake.Store.IAccountOperations operations, string resourceGroupName, string name, Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount BeginCreate(class Microsoft.Azure.Management.DataLake.Store.IAccountOperations operations, string resourceGroupName, string name, class Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions.BeginCreate(Microsoft.Azure.Management.DataLake.Store.IAccountOperations,System.String,System.String,Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreate (operations As IAccountOperations, resourceGroupName As String, name As String, parameters As DataLakeStoreAccount) As DataLakeStoreAccount" />
      <MemberSignature Language="F#" Value="static member BeginCreate : Microsoft.Azure.Management.DataLake.Store.IAccountOperations * string * string * Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount -&gt; Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount" Usage="Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions.BeginCreate (operations, resourceGroupName, name, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Data Lake Store アカウントが含まれている Azure リソース グループの名前。
            </param>
        <param name="name">
            作成する Data Lake Store アカウントの名前。
            </param>
        <param name="parameters">
            Data Lake Store アカウントを作成する指定されたパラメーター。
            </param>
        <summary>
            指定された Data Lake Store アカウントを作成します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount&gt; BeginCreateAsync (this Microsoft.Azure.Management.DataLake.Store.IAccountOperations operations, string resourceGroupName, string name, Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount&gt; BeginCreateAsync(class Microsoft.Azure.Management.DataLake.Store.IAccountOperations operations, string resourceGroupName, string name, class Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions.BeginCreateAsync(Microsoft.Azure.Management.DataLake.Store.IAccountOperations,System.String,System.String,Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateAsync : Microsoft.Azure.Management.DataLake.Store.IAccountOperations * string * string * Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount&gt;" Usage="Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions.BeginCreateAsync (operations, resourceGroupName, name, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions/&lt;BeginCreateAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Data Lake Store アカウントが含まれている Azure リソース グループの名前。
            </param>
        <param name="name">
            作成する Data Lake Store アカウントの名前。
            </param>
        <param name="parameters">
            Data Lake Store アカウントを作成する指定されたパラメーター。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定された Data Lake Store アカウントを作成します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static void BeginDelete (this Microsoft.Azure.Management.DataLake.Store.IAccountOperations operations, string resourceGroupName, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginDelete(class Microsoft.Azure.Management.DataLake.Store.IAccountOperations operations, string resourceGroupName, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions.BeginDelete(Microsoft.Azure.Management.DataLake.Store.IAccountOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginDelete (operations As IAccountOperations, resourceGroupName As String, name As String)" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.DataLake.Store.IAccountOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions.BeginDelete (operations, resourceGroupName, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Data Lake Store アカウントが含まれている Azure リソース グループの名前。
            </param>
        <param name="name">
            削除する Data Lake Store アカウントの名前。
            </param>
        <summary>
            指定された Data Lake Store アカウントを削除します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.DataLake.Store.IAccountOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.DataLake.Store.IAccountOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.DataLake.Store.IAccountOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.DataLake.Store.IAccountOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions/&lt;BeginDeleteAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Data Lake Store アカウントが含まれている Azure リソース グループの名前。
            </param>
        <param name="name">
            削除する Data Lake Store アカウントの名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定された Data Lake Store アカウントを削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount BeginUpdate (this Microsoft.Azure.Management.DataLake.Store.IAccountOperations operations, string resourceGroupName, string name, Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount BeginUpdate(class Microsoft.Azure.Management.DataLake.Store.IAccountOperations operations, string resourceGroupName, string name, class Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions.BeginUpdate(Microsoft.Azure.Management.DataLake.Store.IAccountOperations,System.String,System.String,Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginUpdate (operations As IAccountOperations, resourceGroupName As String, name As String, parameters As DataLakeStoreAccountUpdateParameters) As DataLakeStoreAccount" />
      <MemberSignature Language="F#" Value="static member BeginUpdate : Microsoft.Azure.Management.DataLake.Store.IAccountOperations * string * string * Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountUpdateParameters -&gt; Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount" Usage="Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions.BeginUpdate (operations, resourceGroupName, name, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Data Lake Store アカウントが含まれている Azure リソース グループの名前。
            </param>
        <param name="name">
            更新する Data Lake Store アカウントの名前。
            </param>
        <param name="parameters">
            Data Lake Store アカウントの更新に指定するパラメーターです。
            </param>
        <summary>
            指定した Data Lake Store アカウント情報を更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount&gt; BeginUpdateAsync (this Microsoft.Azure.Management.DataLake.Store.IAccountOperations operations, string resourceGroupName, string name, Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountUpdateParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount&gt; BeginUpdateAsync(class Microsoft.Azure.Management.DataLake.Store.IAccountOperations operations, string resourceGroupName, string name, class Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountUpdateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions.BeginUpdateAsync(Microsoft.Azure.Management.DataLake.Store.IAccountOperations,System.String,System.String,Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountUpdateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginUpdateAsync : Microsoft.Azure.Management.DataLake.Store.IAccountOperations * string * string * Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount&gt;" Usage="Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions.BeginUpdateAsync (operations, resourceGroupName, name, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions/&lt;BeginUpdateAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountUpdateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Data Lake Store アカウントが含まれている Azure リソース グループの名前。
            </param>
        <param name="name">
            更新する Data Lake Store アカウントの名前。
            </param>
        <param name="parameters">
            Data Lake Store アカウントの更新に指定するパラメーターです。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定した Data Lake Store アカウント情報を更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount Create (this Microsoft.Azure.Management.DataLake.Store.IAccountOperations operations, string resourceGroupName, string name, Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount Create(class Microsoft.Azure.Management.DataLake.Store.IAccountOperations operations, string resourceGroupName, string name, class Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions.Create(Microsoft.Azure.Management.DataLake.Store.IAccountOperations,System.String,System.String,Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Create (operations As IAccountOperations, resourceGroupName As String, name As String, parameters As DataLakeStoreAccount) As DataLakeStoreAccount" />
      <MemberSignature Language="F#" Value="static member Create : Microsoft.Azure.Management.DataLake.Store.IAccountOperations * string * string * Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount -&gt; Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount" Usage="Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions.Create (operations, resourceGroupName, name, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Data Lake Store アカウントが含まれている Azure リソース グループの名前。
            </param>
        <param name="name">
            作成する Data Lake Store アカウントの名前。
            </param>
        <param name="parameters">
            Data Lake Store アカウントを作成する指定されたパラメーター。
            </param>
        <summary>
            指定された Data Lake Store アカウントを作成します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount&gt; CreateAsync (this Microsoft.Azure.Management.DataLake.Store.IAccountOperations operations, string resourceGroupName, string name, Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount&gt; CreateAsync(class Microsoft.Azure.Management.DataLake.Store.IAccountOperations operations, string resourceGroupName, string name, class Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions.CreateAsync(Microsoft.Azure.Management.DataLake.Store.IAccountOperations,System.String,System.String,Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : Microsoft.Azure.Management.DataLake.Store.IAccountOperations * string * string * Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount&gt;" Usage="Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions.CreateAsync (operations, resourceGroupName, name, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions/&lt;CreateAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Data Lake Store アカウントが含まれている Azure リソース グループの名前。
            </param>
        <param name="name">
            作成する Data Lake Store アカウントの名前。
            </param>
        <param name="parameters">
            Data Lake Store アカウントを作成する指定されたパラメーター。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定された Data Lake Store アカウントを作成します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.DataLake.Store.IAccountOperations operations, string resourceGroupName, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.DataLake.Store.IAccountOperations operations, string resourceGroupName, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions.Delete(Microsoft.Azure.Management.DataLake.Store.IAccountOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IAccountOperations, resourceGroupName As String, name As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.DataLake.Store.IAccountOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions.Delete (operations, resourceGroupName, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Data Lake Store アカウントが含まれている Azure リソース グループの名前。
            </param>
        <param name="name">
            削除する Data Lake Store アカウントの名前。
            </param>
        <summary>
            指定された Data Lake Store アカウントを削除します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.DataLake.Store.IAccountOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.DataLake.Store.IAccountOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.DataLake.Store.IAccountOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.DataLake.Store.IAccountOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions.DeleteAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions/&lt;DeleteAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Data Lake Store アカウントが含まれている Azure リソース グループの名前。
            </param>
        <param name="name">
            削除する Data Lake Store アカウントの名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定された Data Lake Store アカウントを削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableKeyVault">
      <MemberSignature Language="C#" Value="public static void EnableKeyVault (this Microsoft.Azure.Management.DataLake.Store.IAccountOperations operations, string resourceGroupName, string accountName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void EnableKeyVault(class Microsoft.Azure.Management.DataLake.Store.IAccountOperations operations, string resourceGroupName, string accountName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions.EnableKeyVault(Microsoft.Azure.Management.DataLake.Store.IAccountOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub EnableKeyVault (operations As IAccountOperations, resourceGroupName As String, accountName As String)" />
      <MemberSignature Language="F#" Value="static member EnableKeyVault : Microsoft.Azure.Management.DataLake.Store.IAccountOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions.EnableKeyVault (operations, resourceGroupName, accountName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Data Lake Store アカウントが含まれている Azure リソース グループの名前。
            </param>
        <param name="accountName">
            Key Vault を有効にしようとする Data Lake Store アカウントの名前。
            </param>
        <summary>
            ユーザーを有効にしようとは、指定された Data Lake Store アカウントの暗号化の Key Vault を管理します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableKeyVaultAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task EnableKeyVaultAsync (this Microsoft.Azure.Management.DataLake.Store.IAccountOperations operations, string resourceGroupName, string accountName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task EnableKeyVaultAsync(class Microsoft.Azure.Management.DataLake.Store.IAccountOperations operations, string resourceGroupName, string accountName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions.EnableKeyVaultAsync(Microsoft.Azure.Management.DataLake.Store.IAccountOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member EnableKeyVaultAsync : Microsoft.Azure.Management.DataLake.Store.IAccountOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions.EnableKeyVaultAsync (operations, resourceGroupName, accountName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions/&lt;EnableKeyVaultAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Data Lake Store アカウントが含まれている Azure リソース グループの名前。
            </param>
        <param name="accountName">
            Key Vault を有効にしようとする Data Lake Store アカウントの名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            ユーザーを有効にしようとは、指定された Data Lake Store アカウントの暗号化の Key Vault を管理します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Exists">
      <MemberSignature Language="C#" Value="public static bool Exists (this Microsoft.Azure.Management.DataLake.Store.IAccountOperations operations, string resourceGroupName, string accountName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig bool Exists(class Microsoft.Azure.Management.DataLake.Store.IAccountOperations operations, string resourceGroupName, string accountName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions.Exists(Microsoft.Azure.Management.DataLake.Store.IAccountOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Exists (operations As IAccountOperations, resourceGroupName As String, accountName As String) As Boolean" />
      <MemberSignature Language="F#" Value="static member Exists : Microsoft.Azure.Management.DataLake.Store.IAccountOperations * string * string -&gt; bool" Usage="Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions.Exists (operations, resourceGroupName, accountName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Data Lake Store アカウントが含まれている Azure リソース グループの名前。
            </param>
        <param name="accountName">
            取得する Data Lake Store アカウントの名前。
            </param>
        <summary>
            指定された Data Lake Store アカウントを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExistsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;bool&gt; ExistsAsync (this Microsoft.Azure.Management.DataLake.Store.IAccountOperations operations, string resourceGroupName, string accountName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;bool&gt; ExistsAsync(class Microsoft.Azure.Management.DataLake.Store.IAccountOperations operations, string resourceGroupName, string accountName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions.ExistsAsync(Microsoft.Azure.Management.DataLake.Store.IAccountOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ExistsAsync : Microsoft.Azure.Management.DataLake.Store.IAccountOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions.ExistsAsync (operations, resourceGroupName, accountName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions/&lt;ExistsAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Data Lake Store アカウントが含まれている Azure リソース グループの名前。
            </param>
        <param name="accountName">
            取得する Data Lake Store アカウントの名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定された Data Lake Store アカウントを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FirewallRuleExists">
      <MemberSignature Language="C#" Value="public static bool FirewallRuleExists (this Microsoft.Azure.Management.DataLake.Store.IAccountOperations operations, string resourceGroupName, string accountName, string firewallRuleName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig bool FirewallRuleExists(class Microsoft.Azure.Management.DataLake.Store.IAccountOperations operations, string resourceGroupName, string accountName, string firewallRuleName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions.FirewallRuleExists(Microsoft.Azure.Management.DataLake.Store.IAccountOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function FirewallRuleExists (operations As IAccountOperations, resourceGroupName As String, accountName As String, firewallRuleName As String) As Boolean" />
      <MemberSignature Language="F#" Value="static member FirewallRuleExists : Microsoft.Azure.Management.DataLake.Store.IAccountOperations * string * string * string -&gt; bool" Usage="Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions.FirewallRuleExists (operations, resourceGroupName, accountName, firewallRuleName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="firewallRuleName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Data Lake Store アカウントが含まれている Azure リソース グループの名前。
            </param>
        <param name="accountName">
            ファイアウォール ルールの取得元の Data Lake Store アカウントの名前。
            </param>
        <param name="firewallRuleName">
            取得するファイアウォール規則の名前。
            </param>
        <summary>
            指定された Data Lake Store のファイアウォール ルールを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FirewallRuleExistsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;bool&gt; FirewallRuleExistsAsync (this Microsoft.Azure.Management.DataLake.Store.IAccountOperations operations, string resourceGroupName, string accountName, string firewallRuleName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;bool&gt; FirewallRuleExistsAsync(class Microsoft.Azure.Management.DataLake.Store.IAccountOperations operations, string resourceGroupName, string accountName, string firewallRuleName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions.FirewallRuleExistsAsync(Microsoft.Azure.Management.DataLake.Store.IAccountOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member FirewallRuleExistsAsync : Microsoft.Azure.Management.DataLake.Store.IAccountOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions.FirewallRuleExistsAsync (operations, resourceGroupName, accountName, firewallRuleName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions/&lt;FirewallRuleExistsAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="firewallRuleName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Data Lake Store アカウントが含まれている Azure リソース グループの名前。
            </param>
        <param name="accountName">
            ファイアウォール ルールの取得元の Data Lake Store アカウントの名前。
            </param>
        <param name="firewallRuleName">
            取得するファイアウォール規則の名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定された Data Lake Store のファイアウォール ルールを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount Get (this Microsoft.Azure.Management.DataLake.Store.IAccountOperations operations, string resourceGroupName, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount Get(class Microsoft.Azure.Management.DataLake.Store.IAccountOperations operations, string resourceGroupName, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions.Get(Microsoft.Azure.Management.DataLake.Store.IAccountOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IAccountOperations, resourceGroupName As String, name As String) As DataLakeStoreAccount" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.DataLake.Store.IAccountOperations * string * string -&gt; Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount" Usage="Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions.Get (operations, resourceGroupName, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Data Lake Store アカウントが含まれている Azure リソース グループの名前。
            </param>
        <param name="name">
            取得する Data Lake Store アカウントの名前。
            </param>
        <summary>
            指定された Data Lake Store アカウントを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount&gt; GetAsync (this Microsoft.Azure.Management.DataLake.Store.IAccountOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount&gt; GetAsync(class Microsoft.Azure.Management.DataLake.Store.IAccountOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions.GetAsync(Microsoft.Azure.Management.DataLake.Store.IAccountOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.DataLake.Store.IAccountOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount&gt;" Usage="Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions.GetAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions/&lt;GetAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Data Lake Store アカウントが含まれている Azure リソース グループの名前。
            </param>
        <param name="name">
            取得する Data Lake Store アカウントの名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定された Data Lake Store アカウントを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountBasic&gt; List (this Microsoft.Azure.Management.DataLake.Store.IAccountOperations operations, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount&gt; odataQuery = null, string select = null, Nullable&lt;bool&gt; count = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountBasic&gt; List(class Microsoft.Azure.Management.DataLake.Store.IAccountOperations operations, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount&gt; odataQuery, string select, valuetype System.Nullable`1&lt;bool&gt; count) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions.List(Microsoft.Azure.Management.DataLake.Store.IAccountOperations,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount},System.String,System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IAccountOperations, Optional odataQuery As ODataQuery(Of DataLakeStoreAccount) = null, Optional select As String = null, Optional count As Nullable(Of Boolean) = null) As IPage(Of DataLakeStoreAccountBasic)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.DataLake.Store.IAccountOperations * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount&gt; * string * Nullable&lt;bool&gt; -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountBasic&gt;" Usage="Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions.List (operations, odataQuery, select, count)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountBasic&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IAccountOperations" RefType="this" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="odataQuery">
            OData の操作に適用するパラメーター。
            </param>
        <param name="select">
            OData の Select ステートメント。 各エントリのためだけに要求されると、カテゴリなどのプロパティを制限しますか? $select = CategoryName、説明します。 省略可能。
            </param>
        <param name="count">
            応答、カテゴリなどのリソースに含まれている一致するリソースの数を要求を true または false のブール値。 $count = true です。 省略可能。
            </param>
        <summary>
            サブスクリプション内での Data Lake Store アカウントを一覧表示します。 応答には、存在する場合、結果の次のページへのリンクが含まれています。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountBasic&gt;&gt; ListAsync (this Microsoft.Azure.Management.DataLake.Store.IAccountOperations operations, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount&gt; odataQuery = null, string select = null, Nullable&lt;bool&gt; count = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountBasic&gt;&gt; ListAsync(class Microsoft.Azure.Management.DataLake.Store.IAccountOperations operations, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount&gt; odataQuery, string select, valuetype System.Nullable`1&lt;bool&gt; count, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions.ListAsync(Microsoft.Azure.Management.DataLake.Store.IAccountOperations,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount},System.String,System.Nullable{System.Boolean},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.DataLake.Store.IAccountOperations * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount&gt; * string * Nullable&lt;bool&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountBasic&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions.ListAsync (operations, odataQuery, select, count, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions/&lt;ListAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountBasic&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IAccountOperations" RefType="this" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="odataQuery">
            OData の操作に適用するパラメーター。
            </param>
        <param name="select">
            OData の Select ステートメント。 各エントリのためだけに要求されると、カテゴリなどのプロパティを制限しますか? $select = CategoryName、説明します。 省略可能。
            </param>
        <param name="count">
            応答、カテゴリなどのリソースに含まれている一致するリソースの数を要求を true または false のブール値。 $count = true です。 省略可能。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            サブスクリプション内での Data Lake Store アカウントを一覧表示します。 応答には、存在する場合、結果の次のページへのリンクが含まれています。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroup">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountBasic&gt; ListByResourceGroup (this Microsoft.Azure.Management.DataLake.Store.IAccountOperations operations, string resourceGroupName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount&gt; odataQuery = null, string select = null, Nullable&lt;bool&gt; count = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountBasic&gt; ListByResourceGroup(class Microsoft.Azure.Management.DataLake.Store.IAccountOperations operations, string resourceGroupName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount&gt; odataQuery, string select, valuetype System.Nullable`1&lt;bool&gt; count) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions.ListByResourceGroup(Microsoft.Azure.Management.DataLake.Store.IAccountOperations,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount},System.String,System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByResourceGroup (operations As IAccountOperations, resourceGroupName As String, Optional odataQuery As ODataQuery(Of DataLakeStoreAccount) = null, Optional select As String = null, Optional count As Nullable(Of Boolean) = null) As IPage(Of DataLakeStoreAccountBasic)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroup : Microsoft.Azure.Management.DataLake.Store.IAccountOperations * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount&gt; * string * Nullable&lt;bool&gt; -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountBasic&gt;" Usage="Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions.ListByResourceGroup (operations, resourceGroupName, odataQuery, select, count)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountBasic&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Data Lake Store アカウントが含まれている Azure リソース グループの名前。
            </param>
        <param name="odataQuery">
            OData の操作に適用するパラメーター。
            </param>
        <param name="select">
            OData の Select ステートメント。 各エントリのためだけに要求されると、カテゴリなどのプロパティを制限しますか? $select = CategoryName、説明します。 省略可能。
            </param>
        <param name="count">
            ブール値 true または false などのカテゴリ、応答内のリソースに含まれている一致するリソースの数を要求するのですか? $count = true です。 省略可能。
            </param>
        <summary>
            特定のリソース グループ内の Data Lake Store アカウントを一覧表示します。 応答には、存在する場合、結果の次のページへのリンクが含まれています。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountBasic&gt;&gt; ListByResourceGroupAsync (this Microsoft.Azure.Management.DataLake.Store.IAccountOperations operations, string resourceGroupName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount&gt; odataQuery = null, string select = null, Nullable&lt;bool&gt; count = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountBasic&gt;&gt; ListByResourceGroupAsync(class Microsoft.Azure.Management.DataLake.Store.IAccountOperations operations, string resourceGroupName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount&gt; odataQuery, string select, valuetype System.Nullable`1&lt;bool&gt; count, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions.ListByResourceGroupAsync(Microsoft.Azure.Management.DataLake.Store.IAccountOperations,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount},System.String,System.Nullable{System.Boolean},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupAsync : Microsoft.Azure.Management.DataLake.Store.IAccountOperations * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount&gt; * string * Nullable&lt;bool&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountBasic&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions.ListByResourceGroupAsync (operations, resourceGroupName, odataQuery, select, count, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions/&lt;ListByResourceGroupAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountBasic&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Data Lake Store アカウントが含まれている Azure リソース グループの名前。
            </param>
        <param name="odataQuery">
            OData の操作に適用するパラメーター。
            </param>
        <param name="select">
            OData の Select ステートメント。 各エントリのためだけに要求されると、カテゴリなどのプロパティを制限しますか? $select = CategoryName、説明します。 省略可能。
            </param>
        <param name="count">
            ブール値 true または false などのカテゴリ、応答内のリソースに含まれている一致するリソースの数を要求するのですか? $count = true です。 省略可能。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            特定のリソース グループ内の Data Lake Store アカウントを一覧表示します。 応答には、存在する場合、結果の次のページへのリンクが含まれています。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountBasic&gt; ListByResourceGroupNext (this Microsoft.Azure.Management.DataLake.Store.IAccountOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountBasic&gt; ListByResourceGroupNext(class Microsoft.Azure.Management.DataLake.Store.IAccountOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions.ListByResourceGroupNext(Microsoft.Azure.Management.DataLake.Store.IAccountOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByResourceGroupNext (operations As IAccountOperations, nextPageLink As String) As IPage(Of DataLakeStoreAccountBasic)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNext : Microsoft.Azure.Management.DataLake.Store.IAccountOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountBasic&gt;" Usage="Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions.ListByResourceGroupNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountBasic&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IAccountOperations" RefType="this" />
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
            特定のリソース グループ内の Data Lake Store アカウントを一覧表示します。 応答には、存在する場合、結果の次のページへのリンクが含まれています。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountBasic&gt;&gt; ListByResourceGroupNextAsync (this Microsoft.Azure.Management.DataLake.Store.IAccountOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountBasic&gt;&gt; ListByResourceGroupNextAsync(class Microsoft.Azure.Management.DataLake.Store.IAccountOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions.ListByResourceGroupNextAsync(Microsoft.Azure.Management.DataLake.Store.IAccountOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNextAsync : Microsoft.Azure.Management.DataLake.Store.IAccountOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountBasic&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions.ListByResourceGroupNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions/&lt;ListByResourceGroupNextAsync&gt;d__25))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountBasic&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IAccountOperations" RefType="this" />
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
            特定のリソース グループ内の Data Lake Store アカウントを一覧表示します。 応答には、存在する場合、結果の次のページへのリンクが含まれています。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountBasic&gt; ListNext (this Microsoft.Azure.Management.DataLake.Store.IAccountOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountBasic&gt; ListNext(class Microsoft.Azure.Management.DataLake.Store.IAccountOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions.ListNext(Microsoft.Azure.Management.DataLake.Store.IAccountOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IAccountOperations, nextPageLink As String) As IPage(Of DataLakeStoreAccountBasic)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.DataLake.Store.IAccountOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountBasic&gt;" Usage="Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountBasic&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IAccountOperations" RefType="this" />
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
            サブスクリプション内での Data Lake Store アカウントを一覧表示します。 応答には、存在する場合、結果の次のページへのリンクが含まれています。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountBasic&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.DataLake.Store.IAccountOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountBasic&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.DataLake.Store.IAccountOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.DataLake.Store.IAccountOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.DataLake.Store.IAccountOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountBasic&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions/&lt;ListNextAsync&gt;d__27))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountBasic&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IAccountOperations" RefType="this" />
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
            サブスクリプション内での Data Lake Store アカウントを一覧表示します。 応答には、存在する場合、結果の次のページへのリンクが含まれています。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount Update (this Microsoft.Azure.Management.DataLake.Store.IAccountOperations operations, string resourceGroupName, string name, Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount Update(class Microsoft.Azure.Management.DataLake.Store.IAccountOperations operations, string resourceGroupName, string name, class Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions.Update(Microsoft.Azure.Management.DataLake.Store.IAccountOperations,System.String,System.String,Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Update (operations As IAccountOperations, resourceGroupName As String, name As String, parameters As DataLakeStoreAccountUpdateParameters) As DataLakeStoreAccount" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Management.DataLake.Store.IAccountOperations * string * string * Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountUpdateParameters -&gt; Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount" Usage="Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions.Update (operations, resourceGroupName, name, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Data Lake Store アカウントが含まれている Azure リソース グループの名前。
            </param>
        <param name="name">
            更新する Data Lake Store アカウントの名前。
            </param>
        <param name="parameters">
            Data Lake Store アカウントの更新に指定するパラメーターです。
            </param>
        <summary>
            指定した Data Lake Store アカウント情報を更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount&gt; UpdateAsync (this Microsoft.Azure.Management.DataLake.Store.IAccountOperations operations, string resourceGroupName, string name, Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountUpdateParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount&gt; UpdateAsync(class Microsoft.Azure.Management.DataLake.Store.IAccountOperations operations, string resourceGroupName, string name, class Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountUpdateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.DataLake.Store.IAccountOperations,System.String,System.String,Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountUpdateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.DataLake.Store.IAccountOperations * string * string * Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount&gt;" Usage="Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions.UpdateAsync (operations, resourceGroupName, name, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Store.AccountOperationsExtensions/&lt;UpdateAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountUpdateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Data Lake Store アカウントが含まれている Azure リソース グループの名前。
            </param>
        <param name="name">
            更新する Data Lake Store アカウントの名前。
            </param>
        <param name="parameters">
            Data Lake Store アカウントの更新に指定するパラメーターです。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定した Data Lake Store アカウント情報を更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>