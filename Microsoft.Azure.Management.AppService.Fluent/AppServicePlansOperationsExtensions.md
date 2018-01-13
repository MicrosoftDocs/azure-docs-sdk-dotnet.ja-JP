<Type Name="AppServicePlansOperationsExtensions" FullName="Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class AppServicePlansOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit AppServicePlansOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module AppServicePlansOperationsExtensions" />
  <TypeSignature Language="F#" Value="type AppServicePlansOperationsExtensions = class" />
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
            AppServicePlansOperations の拡張メソッド。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string resourceGroupName, string name, Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner appServicePlan, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string resourceGroupName, string name, class Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner appServicePlan, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations,System.String,System.String,Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations * string * string * Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, name, appServicePlan, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__26))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="appServicePlan" Type="Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースが属するリソース グループの名前です。
            </param>
        <param name="name">
            App Service プランの名前です。
            </param>
        <param name="appServicePlan">
            App Service の詳細を計画します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            作成するか、App Service プランを更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            作成するか、App Service プランを更新します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string resourceGroupName, string name, Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner appServicePlan, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string resourceGroupName, string name, class Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner appServicePlan, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations,System.String,System.String,Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations * string * string * Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, name, appServicePlan, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="appServicePlan" Type="Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースが属するリソース グループの名前です。
            </param>
        <param name="name">
            App Service プランの名前です。
            </param>
        <param name="appServicePlan">
            App Service の詳細を計画します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            作成するか、App Service プランを更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            作成するか、App Service プランを更新します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateVnetRouteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.VnetRouteInner&gt; CreateOrUpdateVnetRouteAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string resourceGroupName, string name, string vnetName, string routeName, Microsoft.Azure.Management.AppService.Fluent.Models.VnetRouteInner route, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.VnetRouteInner&gt; CreateOrUpdateVnetRouteAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string resourceGroupName, string name, string vnetName, string routeName, class Microsoft.Azure.Management.AppService.Fluent.Models.VnetRouteInner route, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.CreateOrUpdateVnetRouteAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.AppService.Fluent.Models.VnetRouteInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateVnetRouteAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations * string * string * string * string * Microsoft.Azure.Management.AppService.Fluent.Models.VnetRouteInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.VnetRouteInner&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.CreateOrUpdateVnetRouteAsync (operations, resourceGroupName, name, vnetName, routeName, route, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions/&lt;CreateOrUpdateVnetRouteAsync&gt;d__22))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.VnetRouteInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="vnetName" Type="System.String" />
        <Parameter Name="routeName" Type="System.String" />
        <Parameter Name="route" Type="Microsoft.Azure.Management.AppService.Fluent.Models.VnetRouteInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースが属するリソース グループの名前です。
            </param>
        <param name="name">
            App Service プランの名前です。
            </param>
        <param name="vnetName">
            仮想ネットワークの名前です。
            </param>
        <param name="routeName">
            仮想ネットワーク ルートの名前です。
            </param>
        <param name="route">
            仮想ネットワーク ルートを定義します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            作成または、App Service プラン内の仮想ネットワーク ルートを更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            作成または、App Service プラン内の仮想ネットワーク ルートを更新します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.DeleteAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions/&lt;DeleteAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
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
        <param name="name">
            App Service プランの名前です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            App Service プランを削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            App Service プランを削除します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteHybridConnectionAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteHybridConnectionAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string resourceGroupName, string name, string namespaceName, string relayName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteHybridConnectionAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string resourceGroupName, string name, string namespaceName, string relayName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.DeleteHybridConnectionAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteHybridConnectionAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.DeleteHybridConnectionAsync (operations, resourceGroupName, name, namespaceName, relayName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions/&lt;DeleteHybridConnectionAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="relayName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースが属するリソース グループの名前です。
            </param>
        <param name="name">
            App Service プランの名前です。
            </param>
        <param name="namespaceName">
            Service Bus 名前空間の名前です。
            </param>
        <param name="relayName">
            Service Bus リレーの名前です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            App Service プラン内で使用するハイブリッド接続を削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            App Service プラン内で使用するハイブリッド接続を削除します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteVnetRouteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteVnetRouteAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string resourceGroupName, string name, string vnetName, string routeName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteVnetRouteAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string resourceGroupName, string name, string vnetName, string routeName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.DeleteVnetRouteAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteVnetRouteAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.DeleteVnetRouteAsync (operations, resourceGroupName, name, vnetName, routeName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions/&lt;DeleteVnetRouteAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="vnetName" Type="System.String" />
        <Parameter Name="routeName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースが属するリソース グループの名前です。
            </param>
        <param name="name">
            App Service プランの名前です。
            </param>
        <param name="vnetName">
            仮想ネットワークの名前です。
            </param>
        <param name="routeName">
            仮想ネットワーク ルートの名前です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            App Service プラン内の仮想ネットワーク ルートを削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            App Service プラン内の仮想ネットワーク ルートを削除します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner&gt; GetAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner&gt; GetAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.GetAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.GetAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions/&lt;GetAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
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
        <param name="name">
            App Service プランの名前です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            App Service プランを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            App Service プランを取得します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetHybridConnectionAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.HybridConnectionInner&gt; GetHybridConnectionAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string resourceGroupName, string name, string namespaceName, string relayName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.HybridConnectionInner&gt; GetHybridConnectionAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string resourceGroupName, string name, string namespaceName, string relayName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.GetHybridConnectionAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetHybridConnectionAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.HybridConnectionInner&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.GetHybridConnectionAsync (operations, resourceGroupName, name, namespaceName, relayName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions/&lt;GetHybridConnectionAsync&gt;d__6))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.HybridConnectionInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="relayName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースが属するリソース グループの名前です。
            </param>
        <param name="name">
            App Service プランの名前です。
            </param>
        <param name="namespaceName">
            Service Bus 名前空間の名前です。
            </param>
        <param name="relayName">
            Service Bus リレーの名前です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            App Service プラン内で使用するハイブリッド接続を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            App Service プラン内で使用するハイブリッド接続を取得します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetHybridConnectionPlanLimitAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.HybridConnectionLimitsInner&gt; GetHybridConnectionPlanLimitAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.HybridConnectionLimitsInner&gt; GetHybridConnectionPlanLimitAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.GetHybridConnectionPlanLimitAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetHybridConnectionPlanLimitAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.HybridConnectionLimitsInner&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.GetHybridConnectionPlanLimitAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions/&lt;GetHybridConnectionPlanLimitAsync&gt;d__10))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.HybridConnectionLimitsInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
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
        <param name="name">
            App Service プランの名前です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            App Service プランで許可されているハイブリッド接続の最大数を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            App Service プランで許可されているハイブリッド接続の最大数を取得します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRouteForVnetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.VnetRouteInner&gt;&gt; GetRouteForVnetAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string resourceGroupName, string name, string vnetName, string routeName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.VnetRouteInner&gt;&gt; GetRouteForVnetAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string resourceGroupName, string name, string vnetName, string routeName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.GetRouteForVnetAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetRouteForVnetAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.VnetRouteInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.GetRouteForVnetAsync (operations, resourceGroupName, name, vnetName, routeName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions/&lt;GetRouteForVnetAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.VnetRouteInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="vnetName" Type="System.String" />
        <Parameter Name="routeName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースが属するリソース グループの名前です。
            </param>
        <param name="name">
            App Service プランの名前です。
            </param>
        <param name="vnetName">
            仮想ネットワークの名前です。
            </param>
        <param name="routeName">
            仮想ネットワーク ルートの名前です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            App Service プラン内の仮想ネットワーク ルートを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            App Service プラン内の仮想ネットワーク ルートを取得します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetVnetFromServerFarmAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.VnetInfoInner&gt; GetVnetFromServerFarmAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string resourceGroupName, string name, string vnetName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.VnetInfoInner&gt; GetVnetFromServerFarmAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string resourceGroupName, string name, string vnetName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.GetVnetFromServerFarmAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetVnetFromServerFarmAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.VnetInfoInner&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.GetVnetFromServerFarmAsync (operations, resourceGroupName, name, vnetName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions/&lt;GetVnetFromServerFarmAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.VnetInfoInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="vnetName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースが属するリソース グループの名前です。
            </param>
        <param name="name">
            App Service プランの名前です。
            </param>
        <param name="vnetName">
            仮想ネットワークの名前です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            App Service プランに関連付けられている仮想ネットワークを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            App Service プランに関連付けられている仮想ネットワークを取得します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetVnetGatewayAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.VnetGatewayInner&gt; GetVnetGatewayAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string resourceGroupName, string name, string vnetName, string gatewayName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.VnetGatewayInner&gt; GetVnetGatewayAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string resourceGroupName, string name, string vnetName, string gatewayName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.GetVnetGatewayAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetVnetGatewayAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.VnetGatewayInner&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.GetVnetGatewayAsync (operations, resourceGroupName, name, vnetName, gatewayName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions/&lt;GetVnetGatewayAsync&gt;d__18))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.VnetGatewayInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="vnetName" Type="System.String" />
        <Parameter Name="gatewayName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースが属するリソース グループの名前です。
            </param>
        <param name="name">
            App Service プランの名前です。
            </param>
        <param name="vnetName">
            仮想ネットワークの名前です。
            </param>
        <param name="gatewayName">
            ゲートウェイの名前です。 'Primary' のゲートウェイのみがサポートされています。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            仮想ネットワーク ゲートウェイを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            仮想ネットワーク ゲートウェイを取得します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner&gt;&gt; ListAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, Nullable&lt;bool&gt; detailed = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner&gt;&gt; ListAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, valuetype System.Nullable`1&lt;bool&gt; detailed, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.ListAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations,System.Nullable{System.Boolean},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations * Nullable&lt;bool&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.ListAsync (operations, detailed, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions/&lt;ListAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="detailed" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="detailed">
            指定&lt;コード&gt;true&lt;/code&gt;をすべての App Service プランのプロパティを返します。 既定値は&lt;コード&gt;false&lt;/code&gt;プロパティのサブセットが返されます。
            すべてのプロパティの取得には、API の待機時間が増加します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            サブスクリプションのすべての App Service プランを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            サブスクリプションのすべての App Service プランを取得します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner&gt;&gt; ListByResourceGroupAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner&gt;&gt; ListByResourceGroupAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.ListByResourceGroupAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.ListByResourceGroupAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions/&lt;ListByResourceGroupAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations" RefType="this" />
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
            リソース グループ内のすべての App Service プランを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            リソース グループ内のすべての App Service プランを取得します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner&gt;&gt; ListByResourceGroupNextAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner&gt;&gt; ListByResourceGroupNextAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.ListByResourceGroupNextAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNextAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.ListByResourceGroupNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions/&lt;ListByResourceGroupNextAsync&gt;d__28))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations" RefType="this" />
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
            リソース グループ内のすべての App Service プランを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            リソース グループ内のすべての App Service プランを取得します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListCapabilitiesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CapabilityInner&gt;&gt; ListCapabilitiesAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.CapabilityInner&gt;&gt; ListCapabilitiesAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.ListCapabilitiesAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListCapabilitiesAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CapabilityInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.ListCapabilitiesAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions/&lt;ListCapabilitiesAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CapabilityInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
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
        <param name="name">
            App Service プランの名前です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            App Service プランのすべての機能を一覧表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            App Service プランのすべての機能を一覧表示します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListHybridConnectionKeysAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.HybridConnectionKeyInner&gt; ListHybridConnectionKeysAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string resourceGroupName, string name, string namespaceName, string relayName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.HybridConnectionKeyInner&gt; ListHybridConnectionKeysAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string resourceGroupName, string name, string namespaceName, string relayName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.ListHybridConnectionKeysAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListHybridConnectionKeysAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.HybridConnectionKeyInner&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.ListHybridConnectionKeysAsync (operations, resourceGroupName, name, namespaceName, relayName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions/&lt;ListHybridConnectionKeysAsync&gt;d__8))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.HybridConnectionKeyInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="relayName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースが属するリソース グループの名前です。
            </param>
        <param name="name">
            App Service プランの名前です。
            </param>
        <param name="namespaceName">
            Service Bus 名前空間の名前。
            </param>
        <param name="relayName">
            Service Bus リレーの名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            ハイブリッド接続の値と送信のキーの名前を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            ハイブリッド接続の値と送信のキーの名前を取得します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListHybridConnectionsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.HybridConnectionInner&gt;&gt; ListHybridConnectionsAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.HybridConnectionInner&gt;&gt; ListHybridConnectionsAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.ListHybridConnectionsAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListHybridConnectionsAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.HybridConnectionInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.ListHybridConnectionsAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions/&lt;ListHybridConnectionsAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.HybridConnectionInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
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
        <param name="name">
            App Service プランの名前です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            App Service プランで使用中のすべてのハイブリッド接続を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            App Service プランで使用中のすべてのハイブリッド接続を取得します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListHybridConnectionsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.HybridConnectionInner&gt;&gt; ListHybridConnectionsNextAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.HybridConnectionInner&gt;&gt; ListHybridConnectionsNextAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.ListHybridConnectionsNextAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListHybridConnectionsNextAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.HybridConnectionInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.ListHybridConnectionsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions/&lt;ListHybridConnectionsNextAsync&gt;d__30))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.HybridConnectionInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations" RefType="this" />
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
            App Service プランで使用中のすべてのハイブリッド接続を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            App Service プランで使用中のすべてのハイブリッド接続を取得します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMetricDefintionsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricDefinition&gt;&gt; ListMetricDefintionsAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricDefinition&gt;&gt; ListMetricDefintionsAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.ListMetricDefintionsAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListMetricDefintionsAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricDefinition&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.ListMetricDefintionsAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions/&lt;ListMetricDefintionsAsync&gt;d__12))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricDefinition&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="name">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMetricDefintionsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricDefinition&gt;&gt; ListMetricDefintionsNextAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricDefinition&gt;&gt; ListMetricDefintionsNextAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.ListMetricDefintionsNextAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListMetricDefintionsNextAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricDefinition&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.ListMetricDefintionsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions/&lt;ListMetricDefintionsNextAsync&gt;d__31))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricDefinition&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations" RefType="this" />
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
    <Member MemberName="ListMetricsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt; ListMetricsAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string resourceGroupName, string name, Nullable&lt;bool&gt; details = null, string filter = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt; ListMetricsAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string resourceGroupName, string name, valuetype System.Nullable`1&lt;bool&gt; details, string filter, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.ListMetricsAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations,System.String,System.String,System.Nullable{System.Boolean},System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListMetricsAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations * string * string * Nullable&lt;bool&gt; * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.ListMetricsAsync (operations, resourceGroupName, name, details, filter, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions/&lt;ListMetricsAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="details" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="filter" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースが属するリソース グループの名前です。
            </param>
        <param name="name">
            App Service プランの名前です。
            </param>
        <param name="details">
            指定&lt;コード&gt;true&lt;/code&gt;にインスタンスの詳細を含めます。 既定値は&lt;コード&gt;false&lt;/code&gt;です。
            </param>
        <param name="filter">
            使用状況/メトリックのみ、フィルターで指定されたを返します。 フィルターは、odata 構文に準拠します。 例: $filter = (name.value eq 'Metric1' または name.value eq 'Metric2') と startTime eq '2014-01-01T00:00:00Z' と endTime eq' 2014-12-31T23:59:59Z' と timeGrain eq 期間 ' [時間 |分 |1 日]'。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            アプリ サービス プランのメトリックを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            アプリ サービス プランのメトリックを取得します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMetricsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt; ListMetricsNextAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt; ListMetricsNextAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.ListMetricsNextAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListMetricsNextAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.ListMetricsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions/&lt;ListMetricsNextAsync&gt;d__32))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations" RefType="this" />
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
            アプリ サービス プランのメトリックを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            アプリ サービス プランのメトリックを取得します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions/&lt;ListNextAsync&gt;d__27))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations" RefType="this" />
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
            サブスクリプションのすべての App Service プランを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            サブスクリプションのすべての App Service プランを取得します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListRoutesForVnetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.VnetRouteInner&gt;&gt; ListRoutesForVnetAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string resourceGroupName, string name, string vnetName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.VnetRouteInner&gt;&gt; ListRoutesForVnetAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string resourceGroupName, string name, string vnetName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.ListRoutesForVnetAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListRoutesForVnetAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.VnetRouteInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.ListRoutesForVnetAsync (operations, resourceGroupName, name, vnetName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions/&lt;ListRoutesForVnetAsync&gt;d__20))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.VnetRouteInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="vnetName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースが属するリソース グループの名前です。
            </param>
        <param name="name">
            App Service プランの名前です。
            </param>
        <param name="vnetName">
            仮想ネットワークの名前です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            App Service プラン内の仮想ネットワークに関連付けられているすべてのルートを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            App Service プラン内の仮想ネットワークに関連付けられているすべてのルートを取得します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListVnetsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.VnetInfoInner&gt;&gt; ListVnetsAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.VnetInfoInner&gt;&gt; ListVnetsAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.ListVnetsAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListVnetsAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.VnetInfoInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.ListVnetsAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions/&lt;ListVnetsAsync&gt;d__16))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.VnetInfoInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
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
        <param name="name">
            App Service プランの名前です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            App Service プランに関連付けられているすべての仮想ネットワークを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            App Service プランに関連付けられているすべての仮想ネットワークを取得します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListWebAppsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt; ListWebAppsAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string resourceGroupName, string name, string skipToken = null, string filter = null, string top = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt; ListWebAppsAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string resourceGroupName, string name, string skipToken, string filter, string top, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.ListWebAppsAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations,System.String,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListWebAppsAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations * string * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.ListWebAppsAsync (operations, resourceGroupName, name, skipToken, filter, top, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions/&lt;ListWebAppsAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="skipToken" Type="System.String" />
        <Parameter Name="filter" Type="System.String" />
        <Parameter Name="top" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースが属するリソース グループの名前です。
            </param>
        <param name="name">
            App Service プランの名前です。
            </param>
        <param name="skipToken">
            App service プランに関連付けられている webapps の一覧で web アプリに進んでください。
            指定した場合、結果のリスト (など)、skipToken から web アプリが含まれます。 それ以外の場合、結果のリストが一覧の先頭からの web アプリが含まれます
            </param>
        <param name="filter">
            サポートされているフィルター: $filter を実行している状態 eq を = です。 現在実行されている web アプリのみを返します
            </param>
        <param name="top">
            ページ サイズを一覧表示します。 指定すると、結果がページングされています。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            App Service プランに関連付けられているすべてのアプリを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            App Service プランに関連付けられているすべてのアプリを取得します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListWebAppsByHybridConnectionAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;string&gt;&gt; ListWebAppsByHybridConnectionAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string resourceGroupName, string name, string namespaceName, string relayName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;string&gt;&gt; ListWebAppsByHybridConnectionAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string resourceGroupName, string name, string namespaceName, string relayName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.ListWebAppsByHybridConnectionAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListWebAppsByHybridConnectionAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;string&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.ListWebAppsByHybridConnectionAsync (operations, resourceGroupName, name, namespaceName, relayName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions/&lt;ListWebAppsByHybridConnectionAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;System.String&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="relayName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースが属するリソース グループの名前です。
            </param>
        <param name="name">
            App Service プランの名前です。
            </param>
        <param name="namespaceName">
            ハイブリッド接続の名前空間の名前です。
            </param>
        <param name="relayName">
            ハイブリッド接続リレーの名前です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            App Service プランのハイブリッド接続を使用するすべてのアプリを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            App Service プランのハイブリッド接続を使用するすべてのアプリを取得します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListWebAppsByHybridConnectionNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;string&gt;&gt; ListWebAppsByHybridConnectionNextAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;string&gt;&gt; ListWebAppsByHybridConnectionNextAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.ListWebAppsByHybridConnectionNextAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListWebAppsByHybridConnectionNextAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;string&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.ListWebAppsByHybridConnectionNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions/&lt;ListWebAppsByHybridConnectionNextAsync&gt;d__29))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;System.String&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations" RefType="this" />
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
            App Service プランのハイブリッド接続を使用するすべてのアプリを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            App Service プランのハイブリッド接続を使用するすべてのアプリを取得します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListWebAppsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt; ListWebAppsNextAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt; ListWebAppsNextAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.ListWebAppsNextAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListWebAppsNextAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.ListWebAppsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions/&lt;ListWebAppsNextAsync&gt;d__33))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations" RefType="this" />
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
            App Service プランに関連付けられているすべてのアプリを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            App Service プランに関連付けられているすべてのアプリを取得します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RebootWorkerAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task RebootWorkerAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string resourceGroupName, string name, string workerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task RebootWorkerAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string resourceGroupName, string name, string workerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.RebootWorkerAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RebootWorkerAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.RebootWorkerAsync (operations, resourceGroupName, name, workerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions/&lt;RebootWorkerAsync&gt;d__25))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="workerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースが属するリソース グループの名前です。
            </param>
        <param name="name">
            App Service プランの名前です。
            </param>
        <param name="workerName">
            通常 RD. で始まるワーカー コンピューターの名前
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            App Service プラン内のワーカーのコンピューターを再起動します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            App Service プラン内のワーカーのコンピューターを再起動します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RestartWebAppsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task RestartWebAppsAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string resourceGroupName, string name, Nullable&lt;bool&gt; softRestart = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task RestartWebAppsAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string resourceGroupName, string name, valuetype System.Nullable`1&lt;bool&gt; softRestart, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.RestartWebAppsAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations,System.String,System.String,System.Nullable{System.Boolean},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RestartWebAppsAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations * string * string * Nullable&lt;bool&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.RestartWebAppsAsync (operations, resourceGroupName, name, softRestart, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions/&lt;RestartWebAppsAsync&gt;d__14))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="softRestart" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースが属するリソース グループの名前です。
            </param>
        <param name="name">
            App Service プランの名前です。
            </param>
        <param name="softRestart">
            指定&lt;コード&gt;true&lt;/code&gt;かからず、ソフト再起動、構成設定を適用し、必要に応じて、アプリを再起動します。 既定値は&lt;コード&gt;false&lt;/code&gt;を常に再起動し、アプリを reprovisions
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            App Service プラン内のすべてのアプリを再起動します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            App Service プラン内のすべてのアプリを再起動します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateVnetGatewayAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.VnetGatewayInner&gt; UpdateVnetGatewayAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string resourceGroupName, string name, string vnetName, string gatewayName, Microsoft.Azure.Management.AppService.Fluent.Models.VnetGatewayInner connectionEnvelope, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.VnetGatewayInner&gt; UpdateVnetGatewayAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string resourceGroupName, string name, string vnetName, string gatewayName, class Microsoft.Azure.Management.AppService.Fluent.Models.VnetGatewayInner connectionEnvelope, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.UpdateVnetGatewayAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.AppService.Fluent.Models.VnetGatewayInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateVnetGatewayAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations * string * string * string * string * Microsoft.Azure.Management.AppService.Fluent.Models.VnetGatewayInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.VnetGatewayInner&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.UpdateVnetGatewayAsync (operations, resourceGroupName, name, vnetName, gatewayName, connectionEnvelope, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions/&lt;UpdateVnetGatewayAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.VnetGatewayInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="vnetName" Type="System.String" />
        <Parameter Name="gatewayName" Type="System.String" />
        <Parameter Name="connectionEnvelope" Type="Microsoft.Azure.Management.AppService.Fluent.Models.VnetGatewayInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースが属するリソース グループの名前です。
            </param>
        <param name="name">
            App Service プランの名前です。
            </param>
        <param name="vnetName">
            仮想ネットワークの名前です。
            </param>
        <param name="gatewayName">
            ゲートウェイの名前です。 'Primary' のゲートウェイのみがサポートされています。
            </param>
        <param name="connectionEnvelope">
            ゲートウェイの定義です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            仮想ネットワーク ゲートウェイを更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            仮想ネットワーク ゲートウェイを更新します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateVnetRouteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.VnetRouteInner&gt; UpdateVnetRouteAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string resourceGroupName, string name, string vnetName, string routeName, Microsoft.Azure.Management.AppService.Fluent.Models.VnetRouteInner route, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.VnetRouteInner&gt; UpdateVnetRouteAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string resourceGroupName, string name, string vnetName, string routeName, class Microsoft.Azure.Management.AppService.Fluent.Models.VnetRouteInner route, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.UpdateVnetRouteAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.AppService.Fluent.Models.VnetRouteInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateVnetRouteAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations * string * string * string * string * Microsoft.Azure.Management.AppService.Fluent.Models.VnetRouteInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.VnetRouteInner&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.UpdateVnetRouteAsync (operations, resourceGroupName, name, vnetName, routeName, route, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions/&lt;UpdateVnetRouteAsync&gt;d__24))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.VnetRouteInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="vnetName" Type="System.String" />
        <Parameter Name="routeName" Type="System.String" />
        <Parameter Name="route" Type="Microsoft.Azure.Management.AppService.Fluent.Models.VnetRouteInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースが属するリソース グループの名前です。
            </param>
        <param name="name">
            App Service プランの名前です。
            </param>
        <param name="vnetName">
            仮想ネットワークの名前です。
            </param>
        <param name="routeName">
            仮想ネットワーク ルートの名前です。
            </param>
        <param name="route">
            仮想ネットワーク ルートを定義します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            作成または、App Service プラン内の仮想ネットワーク ルートを更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            作成または、App Service プラン内の仮想ネットワーク ルートを更新します。
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>