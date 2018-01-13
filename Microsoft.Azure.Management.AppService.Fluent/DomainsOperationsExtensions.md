<Type Name="DomainsOperationsExtensions" FullName="Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class DomainsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit DomainsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module DomainsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type DomainsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            DomainsOperations の拡張メソッド。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations operations, string resourceGroupName, string domainName, Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner domain, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations operations, string resourceGroupName, string domainName, class Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner domain, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations,System.String,System.String,Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations * string * string * Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, domainName, domain, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="domainName" Type="System.String" />
        <Parameter Name="domain" Type="Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースが属するリソース グループの名前です。
            </param>
        <param name="domainName">
            ドメインの名前です。
            </param>
        <param name="domain">
            ドメインの登録情報。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            作成するか、ドメインを更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            作成するか、ドメインを更新します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CheckAvailabilityAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainAvailablilityCheckResultInner&gt; CheckAvailabilityAsync (this Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations operations, Microsoft.Azure.Management.AppService.Fluent.Models.NameIdentifierInner identifier, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.DomainAvailablilityCheckResultInner&gt; CheckAvailabilityAsync(class Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations operations, class Microsoft.Azure.Management.AppService.Fluent.Models.NameIdentifierInner identifier, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions.CheckAvailabilityAsync(Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations,Microsoft.Azure.Management.AppService.Fluent.Models.NameIdentifierInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CheckAvailabilityAsync : Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations * Microsoft.Azure.Management.AppService.Fluent.Models.NameIdentifierInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainAvailablilityCheckResultInner&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions.CheckAvailabilityAsync (operations, identifier, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions/&lt;CheckAvailabilityAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainAvailablilityCheckResultInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations" RefType="this" />
        <Parameter Name="identifier" Type="Microsoft.Azure.Management.AppService.Fluent.Models.NameIdentifierInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="identifier">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations operations, string resourceGroupName, string domainName, Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner domain, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations operations, string resourceGroupName, string domainName, class Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner domain, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations,System.String,System.String,Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations * string * string * Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, domainName, domain, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__6))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="domainName" Type="System.String" />
        <Parameter Name="domain" Type="Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースが属するリソース グループの名前です。
            </param>
        <param name="domainName">
            ドメインの名前です。
            </param>
        <param name="domain">
            ドメインの登録情報。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            作成するか、ドメインを更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            作成するか、ドメインを更新します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateOwnershipIdentifierAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainOwnershipIdentifierInner&gt; CreateOrUpdateOwnershipIdentifierAsync (this Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations operations, string resourceGroupName, string domainName, string name, Microsoft.Azure.Management.AppService.Fluent.Models.DomainOwnershipIdentifierInner domainOwnershipIdentifier, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.DomainOwnershipIdentifierInner&gt; CreateOrUpdateOwnershipIdentifierAsync(class Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations operations, string resourceGroupName, string domainName, string name, class Microsoft.Azure.Management.AppService.Fluent.Models.DomainOwnershipIdentifierInner domainOwnershipIdentifier, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions.CreateOrUpdateOwnershipIdentifierAsync(Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.AppService.Fluent.Models.DomainOwnershipIdentifierInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateOwnershipIdentifierAsync : Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations * string * string * string * Microsoft.Azure.Management.AppService.Fluent.Models.DomainOwnershipIdentifierInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainOwnershipIdentifierInner&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions.CreateOrUpdateOwnershipIdentifierAsync (operations, resourceGroupName, domainName, name, domainOwnershipIdentifier, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions/&lt;CreateOrUpdateOwnershipIdentifierAsync&gt;d__10))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainOwnershipIdentifierInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="domainName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="domainOwnershipIdentifier" Type="Microsoft.Azure.Management.AppService.Fluent.Models.DomainOwnershipIdentifierInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースが属するリソース グループの名前です。
            </param>
        <param name="domainName">
            ドメインの名前です。
            </param>
        <param name="name">
            識別子の名前です。
            </param>
        <param name="domainOwnershipIdentifier">
            ドメインの所有権プロパティの JSON 表現。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            ドメインまたは更新プログラムの識別子の所有権の識別子を既存の識別子の詳細を作成します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            ドメインまたは更新プログラムの識別子の所有権の識別子を既存の識別子の詳細を作成します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations operations, string resourceGroupName, string domainName, Nullable&lt;bool&gt; forceHardDeleteDomain = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations operations, string resourceGroupName, string domainName, valuetype System.Nullable`1&lt;bool&gt; forceHardDeleteDomain, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations,System.String,System.String,System.Nullable{System.Boolean},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations * string * string * Nullable&lt;bool&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions.DeleteAsync (operations, resourceGroupName, domainName, forceHardDeleteDomain, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions/&lt;DeleteAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="domainName" Type="System.String" />
        <Parameter Name="forceHardDeleteDomain" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースが属するリソース グループの名前です。
            </param>
        <param name="domainName">
            ドメインの名前です。
            </param>
        <param name="forceHardDeleteDomain">
            指定&lt;コード&gt;true&lt;/code&gt;ドメインをすぐに削除します。 既定値は&lt;コード&gt;false&lt;/code&gt; 24 時間後に、ドメインを削除します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            ドメインを削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            ドメインを削除します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteOwnershipIdentifierAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteOwnershipIdentifierAsync (this Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations operations, string resourceGroupName, string domainName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteOwnershipIdentifierAsync(class Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations operations, string resourceGroupName, string domainName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions.DeleteOwnershipIdentifierAsync(Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteOwnershipIdentifierAsync : Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions.DeleteOwnershipIdentifierAsync (operations, resourceGroupName, domainName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions/&lt;DeleteOwnershipIdentifierAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="domainName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースが属するリソース グループの名前です。
            </param>
        <param name="domainName">
            ドメインの名前です。
            </param>
        <param name="name">
            識別子の名前です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            ドメインの所有権の識別子を削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            ドメインの所有権の識別子を削除します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner&gt; GetAsync (this Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations operations, string resourceGroupName, string domainName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner&gt; GetAsync(class Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations operations, string resourceGroupName, string domainName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions.GetAsync(Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions.GetAsync (operations, resourceGroupName, domainName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions/&lt;GetAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="domainName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースが属するリソース グループの名前です。
            </param>
        <param name="domainName">
            ドメインの名前です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            ドメインを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            ドメインを取得します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetControlCenterSsoRequestAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainControlCenterSsoRequestInner&gt; GetControlCenterSsoRequestAsync (this Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.DomainControlCenterSsoRequestInner&gt; GetControlCenterSsoRequestAsync(class Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions.GetControlCenterSsoRequestAsync(Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetControlCenterSsoRequestAsync : Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainControlCenterSsoRequestInner&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions.GetControlCenterSsoRequestAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions/&lt;GetControlCenterSsoRequestAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainControlCenterSsoRequestInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            ドメインの管理ポータルの 1 つのサインオン要求を生成します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            ドメインの管理ポータルの 1 つのサインオン要求を生成します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetOwnershipIdentifierAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainOwnershipIdentifierInner&gt; GetOwnershipIdentifierAsync (this Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations operations, string resourceGroupName, string domainName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.DomainOwnershipIdentifierInner&gt; GetOwnershipIdentifierAsync(class Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations operations, string resourceGroupName, string domainName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions.GetOwnershipIdentifierAsync(Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetOwnershipIdentifierAsync : Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainOwnershipIdentifierInner&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions.GetOwnershipIdentifierAsync (operations, resourceGroupName, domainName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions/&lt;GetOwnershipIdentifierAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainOwnershipIdentifierInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="domainName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースが属するリソース グループの名前です。
            </param>
        <param name="domainName">
            ドメインの名前です。
            </param>
        <param name="name">
            識別子の名前です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            ドメインの所有権の識別子を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            ドメインの所有権の識別子を取得します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner&gt;&gt; ListAsync (this Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner&gt;&gt; ListAsync(class Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions.ListAsync(Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions.ListAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions/&lt;ListAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            サブスクリプションのすべてのドメインを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            サブスクリプションのすべてのドメインを取得します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner&gt;&gt; ListByResourceGroupAsync (this Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner&gt;&gt; ListByResourceGroupAsync(class Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions.ListByResourceGroupAsync(Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupAsync : Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions.ListByResourceGroupAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions/&lt;ListByResourceGroupAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースが属するリソース グループの名前です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            リソース グループ内のすべてのドメインを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            リソース グループ内のすべてのドメインを取得します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner&gt;&gt; ListByResourceGroupNextAsync (this Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner&gt;&gt; ListByResourceGroupNextAsync(class Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions.ListByResourceGroupNextAsync(Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNextAsync : Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions.ListByResourceGroupNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions/&lt;ListByResourceGroupNextAsync&gt;d__16))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations" RefType="this" />
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
            リソース グループ内のすべてのドメインを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            リソース グループ内のすべてのドメインを取得します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions/&lt;ListNextAsync&gt;d__14))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations" RefType="this" />
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
            サブスクリプションのすべてのドメインを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            サブスクリプションのすべてのドメインを取得します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListOwnershipIdentifiersAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainOwnershipIdentifierInner&gt;&gt; ListOwnershipIdentifiersAsync (this Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations operations, string resourceGroupName, string domainName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.DomainOwnershipIdentifierInner&gt;&gt; ListOwnershipIdentifiersAsync(class Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations operations, string resourceGroupName, string domainName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions.ListOwnershipIdentifiersAsync(Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListOwnershipIdentifiersAsync : Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainOwnershipIdentifierInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions.ListOwnershipIdentifiersAsync (operations, resourceGroupName, domainName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions/&lt;ListOwnershipIdentifiersAsync&gt;d__8))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainOwnershipIdentifierInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="domainName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースが属するリソース グループの名前です。
            </param>
        <param name="domainName">
            ドメインの名前です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            ドメインの所有権の識別子を一覧表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            ドメインの所有権の識別子を一覧表示します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListOwnershipIdentifiersNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainOwnershipIdentifierInner&gt;&gt; ListOwnershipIdentifiersNextAsync (this Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.DomainOwnershipIdentifierInner&gt;&gt; ListOwnershipIdentifiersNextAsync(class Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions.ListOwnershipIdentifiersNextAsync(Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListOwnershipIdentifiersNextAsync : Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainOwnershipIdentifierInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions.ListOwnershipIdentifiersNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions/&lt;ListOwnershipIdentifiersNextAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainOwnershipIdentifierInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations" RefType="this" />
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
            ドメインの所有権の識別子を一覧表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            ドメインの所有権の識別子を一覧表示します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListRecommendationsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.NameIdentifierInner&gt;&gt; ListRecommendationsAsync (this Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations operations, Microsoft.Azure.Management.AppService.Fluent.Models.DomainRecommendationSearchParametersInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.NameIdentifierInner&gt;&gt; ListRecommendationsAsync(class Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations operations, class Microsoft.Azure.Management.AppService.Fluent.Models.DomainRecommendationSearchParametersInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions.ListRecommendationsAsync(Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations,Microsoft.Azure.Management.AppService.Fluent.Models.DomainRecommendationSearchParametersInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListRecommendationsAsync : Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations * Microsoft.Azure.Management.AppService.Fluent.Models.DomainRecommendationSearchParametersInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.NameIdentifierInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions.ListRecommendationsAsync (operations, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions/&lt;ListRecommendationsAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.NameIdentifierInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations" RefType="this" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.AppService.Fluent.Models.DomainRecommendationSearchParametersInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="parameters">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListRecommendationsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.NameIdentifierInner&gt;&gt; ListRecommendationsNextAsync (this Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.NameIdentifierInner&gt;&gt; ListRecommendationsNextAsync(class Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions.ListRecommendationsNextAsync(Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListRecommendationsNextAsync : Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.NameIdentifierInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions.ListRecommendationsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions/&lt;ListRecommendationsNextAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.NameIdentifierInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="nextPageLink">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateOwnershipIdentifierAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainOwnershipIdentifierInner&gt; UpdateOwnershipIdentifierAsync (this Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations operations, string resourceGroupName, string domainName, string name, Microsoft.Azure.Management.AppService.Fluent.Models.DomainOwnershipIdentifierInner domainOwnershipIdentifier, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.DomainOwnershipIdentifierInner&gt; UpdateOwnershipIdentifierAsync(class Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations operations, string resourceGroupName, string domainName, string name, class Microsoft.Azure.Management.AppService.Fluent.Models.DomainOwnershipIdentifierInner domainOwnershipIdentifier, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions.UpdateOwnershipIdentifierAsync(Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.AppService.Fluent.Models.DomainOwnershipIdentifierInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateOwnershipIdentifierAsync : Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations * string * string * string * Microsoft.Azure.Management.AppService.Fluent.Models.DomainOwnershipIdentifierInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainOwnershipIdentifierInner&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions.UpdateOwnershipIdentifierAsync (operations, resourceGroupName, domainName, name, domainOwnershipIdentifier, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions/&lt;UpdateOwnershipIdentifierAsync&gt;d__12))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainOwnershipIdentifierInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="domainName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="domainOwnershipIdentifier" Type="Microsoft.Azure.Management.AppService.Fluent.Models.DomainOwnershipIdentifierInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースが属するリソース グループの名前です。
            </param>
        <param name="domainName">
            ドメインの名前です。
            </param>
        <param name="name">
            識別子の名前です。
            </param>
        <param name="domainOwnershipIdentifier">
            ドメインの所有権プロパティの JSON 表現。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            ドメインまたは更新プログラムの識別子の所有権の識別子を既存の識別子の詳細を作成します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            ドメインまたは更新プログラムの識別子の所有権の識別子を既存の識別子の詳細を作成します。
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>