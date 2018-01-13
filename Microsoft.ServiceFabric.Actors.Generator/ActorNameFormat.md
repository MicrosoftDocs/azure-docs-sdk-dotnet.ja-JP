<Type Name="ActorNameFormat" FullName="Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat">
  <TypeSignature Language="C#" Value="public static class ActorNameFormat" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ActorNameFormat extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat" />
  <TypeSignature Language="VB.NET" Value="Public Class ActorNameFormat" />
  <TypeSignature Language="F#" Value="type ActorNameFormat = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            サービス名、アプリケーション名の形式、アクター インターフェイスの型のように名前を生成するための静的メソッドが含まれています。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetActorStateProviderSettingsSectionName">
      <MemberSignature Language="C#" Value="public static string GetActorStateProviderSettingsSectionName (Type actorImplementationType);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GetActorStateProviderSettingsSectionName(class System.Type actorImplementationType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetActorStateProviderSettingsSectionName(System.Type)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetActorStateProviderSettingsSectionName (actorImplementationType As Type) As String" />
      <MemberSignature Language="F#" Value="static member GetActorStateProviderSettingsSectionName : Type -&gt; string" Usage="Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetActorStateProviderSettingsSectionName actorImplementationType" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="actorImplementationType" Type="System.Type" />
      </Parameters>
      <Docs>
        <param name="actorImplementationType">
            アクターを実装するクラスの型。
            </param>
        <summary>
            取得、<see cref="T:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider" />アクター サービス用の構成パッケージで指定された構成セクション名。
            </summary>
        <returns>
            ActorStateProvider 構成セクション名。
            </returns>
        <remarks>
            ActorStateProvider 構成セクションで指定された値を使用して構成します。<see cref="T:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider" /></remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCodePackageName">
      <MemberSignature Language="C#" Value="public static string GetCodePackageName (Type actorImplementationType = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GetCodePackageName(class System.Type actorImplementationType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetCodePackageName(System.Type)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetCodePackageName (Optional actorImplementationType As Type = null) As String" />
      <MemberSignature Language="F#" Value="static member GetCodePackageName : Type -&gt; string" Usage="Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetCodePackageName actorImplementationType" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="actorImplementationType" Type="System.Type" />
      </Parameters>
      <Docs>
        <param name="actorImplementationType">アクターを実装するクラスの型。</param>
        <summary>
            アクターのサービス パッケージで使用されるコード パッケージ名を取得します。
            </summary>
        <returns>コード パッケージの名前。</returns>
        <remarks>コード パッケージ名は、サービスとして内からアクセスできます。<see cref="P:System.Fabric.CodePackageActivationContext.CodePackageName" /></remarks>
      </Docs>
    </Member>
    <Member MemberName="GetConfigPackageName">
      <MemberSignature Language="C#" Value="public static string GetConfigPackageName (Type actorImplementationType = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GetConfigPackageName(class System.Type actorImplementationType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetConfigPackageName(System.Type)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetConfigPackageName (Optional actorImplementationType As Type = null) As String" />
      <MemberSignature Language="F#" Value="static member GetConfigPackageName : Type -&gt; string" Usage="Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetConfigPackageName actorImplementationType" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="actorImplementationType" Type="System.Type" />
      </Parameters>
      <Docs>
        <param name="actorImplementationType">アクターを実装するクラスの型。</param>
        <summary>
            アクター サービス パッケージで使用される構成パッケージ名を取得します。
            </summary>
        <returns>構成パッケージの名前です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetFabricApplicationName">
      <MemberSignature Language="C#" Value="public static string GetFabricApplicationName (string appPrefix);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GetFabricApplicationName(string appPrefix) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetFabricApplicationName(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetFabricApplicationName (appPrefix As String) As String" />
      <MemberSignature Language="F#" Value="static member GetFabricApplicationName : string -&gt; string" Usage="Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetFabricApplicationName appPrefix" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="appPrefix" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="appPrefix">アプリケーション名に使用するプレフィックスです。</param>
        <summary>
            Service Fabric クラスター内のアプリケーションの作成に使用するアプリケーションの名前を取得します。
            </summary>
        <returns>アプリケーションの名前。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetFabricApplicationPackageName">
      <MemberSignature Language="C#" Value="public static string GetFabricApplicationPackageName (string appPrefix);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GetFabricApplicationPackageName(string appPrefix) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetFabricApplicationPackageName(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetFabricApplicationPackageName (appPrefix As String) As String" />
      <MemberSignature Language="F#" Value="static member GetFabricApplicationPackageName : string -&gt; string" Usage="Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetFabricApplicationPackageName appPrefix" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="appPrefix" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="appPrefix">アプリケーション パッケージ名に使用するプレフィックスです。</param>
        <summary>
            アクターの Service Fabric アプリケーションのパッケージを作成するために使用するパッケージ名を取得します。
            </summary>
        <returns>アプリケーション パッケージの名前です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetFabricApplicationTypeName">
      <MemberSignature Language="C#" Value="public static string GetFabricApplicationTypeName (string appPrefix);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GetFabricApplicationTypeName(string appPrefix) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetFabricApplicationTypeName(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetFabricApplicationTypeName (appPrefix As String) As String" />
      <MemberSignature Language="F#" Value="static member GetFabricApplicationTypeName : string -&gt; string" Usage="Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetFabricApplicationTypeName appPrefix" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="appPrefix" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="appPrefix">アプリケーションの種類名に使用するプレフィックスです。</param>
        <summary>
            アクターの Service Fabric アプリケーションのパッケージを作成するときに、アプリケーション マニフェストで使用されるアプリケーションの種類名を取得します。
            </summary>
        <returns>アプリケーションの種類の名前です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetFabricServiceEndpointName">
      <MemberSignature Language="C#" Value="public static string GetFabricServiceEndpointName (Type actorImplementationType);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GetFabricServiceEndpointName(class System.Type actorImplementationType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetFabricServiceEndpointName(System.Type)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetFabricServiceEndpointName (actorImplementationType As Type) As String" />
      <MemberSignature Language="F#" Value="static member GetFabricServiceEndpointName : Type -&gt; string" Usage="Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetFabricServiceEndpointName actorImplementationType" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="actorImplementationType" Type="System.Type" />
      </Parameters>
      <Docs>
        <param name="actorImplementationType">アクターを実装するクラスの型。</param>
        <summary>
            アクター サービスのサービス マニフェストに指定されているアクターの種類のサービス エンドポイントを取得します。
            </summary>
        <returns>サービス エンドポイントの名前。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetFabricServiceName">
      <MemberSignature Language="C#" Value="public static string GetFabricServiceName (Type actorInterfaceType, string serviceName = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GetFabricServiceName(class System.Type actorInterfaceType, string serviceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetFabricServiceName(System.Type,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetFabricServiceName (actorInterfaceType As Type, Optional serviceName As String = null) As String" />
      <MemberSignature Language="F#" Value="static member GetFabricServiceName : Type * string -&gt; string" Usage="Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetFabricServiceName (actorInterfaceType, serviceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="actorInterfaceType" Type="System.Type" />
        <Parameter Name="serviceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="actorInterfaceType">アクター インターフェイスの型。</param>
        <param name="serviceName">アクターの種類をホストするサービスの名前です。 この値が null の場合サービス名は、使用して、actorInterfaceType で作成されます。</param>
        <summary>
            Service Fabric クラスター内のアクターの種類をホストするサービスの名前を取得します。
            </summary>
        <returns>Service Fabric サービスの名前はアクターの種類をホストしています。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetFabricServicePackageName">
      <MemberSignature Language="C#" Value="public static string GetFabricServicePackageName (string servicePackageNamePrefix);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GetFabricServicePackageName(string servicePackageNamePrefix) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetFabricServicePackageName(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetFabricServicePackageName (servicePackageNamePrefix As String) As String" />
      <MemberSignature Language="F#" Value="static member GetFabricServicePackageName : string -&gt; string" Usage="Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetFabricServicePackageName servicePackageNamePrefix" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="servicePackageNamePrefix" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="servicePackageNamePrefix">サービス パッケージ名に使用するプレフィックスです。</param>
        <summary>
            アクターの Service Fabric アプリケーションのパッケージで使用されているサービス パッケージ名を取得します。
            </summary>
        <returns>サービス パッケージ名です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetFabricServiceReplicatorConfigSectionName">
      <MemberSignature Language="C#" Value="public static string GetFabricServiceReplicatorConfigSectionName (Type actorImplementationType);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GetFabricServiceReplicatorConfigSectionName(class System.Type actorImplementationType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetFabricServiceReplicatorConfigSectionName(System.Type)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetFabricServiceReplicatorConfigSectionName (actorImplementationType As Type) As String" />
      <MemberSignature Language="F#" Value="static member GetFabricServiceReplicatorConfigSectionName : Type -&gt; string" Usage="Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetFabricServiceReplicatorConfigSectionName actorImplementationType" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="actorImplementationType" Type="System.Type" />
      </Parameters>
      <Docs>
        <param name="actorImplementationType">アクターを実装するクラスの型。</param>
        <summary>
            取得レプリケーター構成セクションのアクター サービス用の構成パッケージで指定された名前。
            </summary>
        <returns>レプリケーター構成セクション名。</returns>
        <remarks>レプリケーターの構成 セクションで指定された値を使用して構成<see cref="T:System.Fabric.ReplicatorSettings" />アクターの状態のプライマリ レプリカとセカンダリ レプリカの間でレプリケーション用です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetFabricServiceReplicatorEndpointName">
      <MemberSignature Language="C#" Value="public static string GetFabricServiceReplicatorEndpointName (Type actorImplementationType);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GetFabricServiceReplicatorEndpointName(class System.Type actorImplementationType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetFabricServiceReplicatorEndpointName(System.Type)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetFabricServiceReplicatorEndpointName (actorImplementationType As Type) As String" />
      <MemberSignature Language="F#" Value="static member GetFabricServiceReplicatorEndpointName : Type -&gt; string" Usage="Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetFabricServiceReplicatorEndpointName actorImplementationType" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="actorImplementationType" Type="System.Type" />
      </Parameters>
      <Docs>
        <param name="actorImplementationType">アクターを実装するクラスの型。</param>
        <summary>
            アクター サービスのサービス マニフェストに指定されているレプリケーター エンドポイントを取得します。
            </summary>
        <returns>サービスのレプリケーター エンドポイントの名前。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetFabricServiceReplicatorSecurityConfigSectionName">
      <MemberSignature Language="C#" Value="public static string GetFabricServiceReplicatorSecurityConfigSectionName (Type actorImplementationType);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GetFabricServiceReplicatorSecurityConfigSectionName(class System.Type actorImplementationType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetFabricServiceReplicatorSecurityConfigSectionName(System.Type)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetFabricServiceReplicatorSecurityConfigSectionName (actorImplementationType As Type) As String" />
      <MemberSignature Language="F#" Value="static member GetFabricServiceReplicatorSecurityConfigSectionName : Type -&gt; string" Usage="Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetFabricServiceReplicatorSecurityConfigSectionName actorImplementationType" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="actorImplementationType" Type="System.Type" />
      </Parameters>
      <Docs>
        <param name="actorImplementationType">アクターを実装するクラスの型。</param>
        <summary>
            レプリケーター セキュリティの構成セクション アクター サービス用の構成パッケージで指定された名前を取得。
            </summary>
        <returns>レプリケーターのセキュリティの構成セクション名。</returns>
        <remarks>レプリケーターのセキュリティ構成 セクションで指定された値を使用して構成<see cref="P:System.Fabric.ReplicatorSettings.SecurityCredentials" />アクターの状態のプライマリ レプリカとセカンダリ レプリカの間でレプリケーション用です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetFabricServiceReplicatorSecurityCredentialTypeName">
      <MemberSignature Language="C#" Value="public static string GetFabricServiceReplicatorSecurityCredentialTypeName (Type actorImplementationType = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GetFabricServiceReplicatorSecurityCredentialTypeName(class System.Type actorImplementationType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetFabricServiceReplicatorSecurityCredentialTypeName(System.Type)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetFabricServiceReplicatorSecurityCredentialTypeName (Optional actorImplementationType As Type = null) As String" />
      <MemberSignature Language="F#" Value="static member GetFabricServiceReplicatorSecurityCredentialTypeName : Type -&gt; string" Usage="Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetFabricServiceReplicatorSecurityCredentialTypeName actorImplementationType" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="actorImplementationType" Type="System.Type" />
      </Parameters>
      <Docs>
        <param name="actorImplementationType">アクターを実装するクラスの型。</param>
        <summary>
            アクター サービスの構成パッケージで複製物作成会社のセキュリティ構成 セクションで使用される資格情報の型名を取得します。
            </summary>
        <returns>レプリケーター セキュリティ資格情報の種類の名前。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetFabricServiceTransportSettingsSectionName">
      <MemberSignature Language="C#" Value="public static string GetFabricServiceTransportSettingsSectionName (Type actorImplementationType);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GetFabricServiceTransportSettingsSectionName(class System.Type actorImplementationType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetFabricServiceTransportSettingsSectionName(System.Type)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetFabricServiceTransportSettingsSectionName (actorImplementationType As Type) As String" />
      <MemberSignature Language="F#" Value="static member GetFabricServiceTransportSettingsSectionName : Type -&gt; string" Usage="Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetFabricServiceTransportSettingsSectionName actorImplementationType" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="actorImplementationType" Type="System.Type" />
      </Parameters>
      <Docs>
        <param name="actorImplementationType">アクターを実装するクラスの型。</param>
        <summary>
             アクター サービス用の構成パッケージで指定された fabrictransport 構成セクション名を取得します。
             </summary>
        <returns>FabricTransport 構成セクション名。</returns>
        <remarks>FabricTransport 構成セクションで指定された値を使用して構成する<see cref="T:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings" />通信します。
             </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetFabricServiceTypeName">
      <MemberSignature Language="C#" Value="public static string GetFabricServiceTypeName (Type actorImplementationType);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GetFabricServiceTypeName(class System.Type actorImplementationType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetFabricServiceTypeName(System.Type)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetFabricServiceTypeName (actorImplementationType As Type) As String" />
      <MemberSignature Language="F#" Value="static member GetFabricServiceTypeName : Type -&gt; string" Usage="Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetFabricServiceTypeName actorImplementationType" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="actorImplementationType" Type="System.Type" />
      </Parameters>
      <Docs>
        <param name="actorImplementationType">アクターの実装の型。</param>
        <summary>
            アクターのサービス型の名前を取得します。
            </summary>
        <returns>サービス型の名前。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetFabricServiceUri">
      <MemberSignature Language="C#" Value="public static Uri GetFabricServiceUri (Type actorInterfaceType);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Uri GetFabricServiceUri(class System.Type actorInterfaceType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetFabricServiceUri(System.Type)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetFabricServiceUri (actorInterfaceType As Type) As Uri" />
      <MemberSignature Language="F#" Value="static member GetFabricServiceUri : Type -&gt; Uri" Usage="Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetFabricServiceUri actorInterfaceType" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="actorInterfaceType" Type="System.Type" />
      </Parameters>
      <Docs>
        <param name="actorInterfaceType">アクター インターフェイスの型。</param>
        <summary>
            サービスの Service Fabric クラスター内のアクターの種類をホストする Uri を取得します。
            </summary>
        <returns>Service Fabric サービスのアクターの種類をホストしている Uri。</returns>
        <remarks>メソッドからのアプリケーション名を取得しようとします。<see cref="T:System.Fabric.CodePackageActivationContext" />です。
            メソッドはまだアプリケーション名を判別できない場合<see cref="T:System.ArgumentException" />がスローされます。 </remarks>
        <exception cref="T:System.ArgumentException">
            使用してアプリケーションの名前を特定できない場合<see cref="T:System.Fabric.CodePackageActivationContext" />です。
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetFabricServiceUri">
      <MemberSignature Language="C#" Value="public static Uri GetFabricServiceUri (Type actorInterfaceType, Uri applicationUri);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Uri GetFabricServiceUri(class System.Type actorInterfaceType, class System.Uri applicationUri) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetFabricServiceUri(System.Type,System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetFabricServiceUri (actorInterfaceType As Type, applicationUri As Uri) As Uri" />
      <MemberSignature Language="F#" Value="static member GetFabricServiceUri : Type * Uri -&gt; Uri" Usage="Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetFabricServiceUri (actorInterfaceType, applicationUri)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="actorInterfaceType" Type="System.Type" />
        <Parameter Name="applicationUri" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="actorInterfaceType">アクター インターフェイスの型。</param>
        <param name="applicationUri">Service Fabric アプリケーション アクター サービスを含む Uri です。
            アプリケーション名がから取得した場合、この値は null<see cref="P:System.Fabric.CodePackageActivationContext.ApplicationName" />です。</param>
        <summary>
            サービスの Service Fabric クラスター内のアクターの種類をホストする Uri を取得します。
            </summary>
        <returns>Service Fabric サービスのアクターの種類をホストしている Uri。</returns>
        <remarks>メソッドは、actorInterfaceType を使用してサービス名を作成します。 アプリケーション名を取得しようとは applicationUri が null として渡されると場合、<see cref="T:System.Fabric.CodePackageActivationContext" />です。 メソッドはまだアプリケーション名を判別できない場合<see cref="T:System.ArgumentException" />がスローされます。 </remarks>
        <exception cref="T:System.ArgumentException">
            使用してアプリケーションの名前を特定できない場合<see cref="T:System.Fabric.CodePackageActivationContext" />です。
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetFabricServiceUri">
      <MemberSignature Language="C#" Value="public static Uri GetFabricServiceUri (Type actorInterfaceType, string applicationName = null, string serviceName = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Uri GetFabricServiceUri(class System.Type actorInterfaceType, string applicationName, string serviceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetFabricServiceUri(System.Type,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetFabricServiceUri (actorInterfaceType As Type, Optional applicationName As String = null, Optional serviceName As String = null) As Uri" />
      <MemberSignature Language="F#" Value="static member GetFabricServiceUri : Type * string * string -&gt; Uri" Usage="Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetFabricServiceUri (actorInterfaceType, applicationName, serviceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="actorInterfaceType" Type="System.Type" />
        <Parameter Name="applicationName" Type="System.String" />
        <Parameter Name="serviceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="actorInterfaceType">アクター インターフェイスの型。</param>
        <param name="applicationName">Service Fabric アプリケーションの名前を含む、アクター サービス。
            アプリケーション名がから取得した場合、この値は null<see cref="P:System.Fabric.CodePackageActivationContext.ApplicationName" />です。</param>
        <param name="serviceName">アクターの種類をホストするサービスの名前です。 この値が null の場合サービス名は、使用して、actorInterfaceType で作成されます。</param>
        <summary>
            サービスの Service Fabric クラスター内のアクターの種類をホストする Uri を取得します。
            </summary>
        <returns>Service Fabric サービスのアクターの種類をホストしている Uri。</returns>
        <remarks>アプリケーション名を取得しようとは、applicationName が null または空の文字列として渡されると場合、<see cref="T:System.Fabric.CodePackageActivationContext" />です。 メソッドはまだアプリケーション名を判別できない場合<see cref="T:System.ArgumentException" />がスローされます。 </remarks>
        <exception cref="T:System.ArgumentException">
            使用して applicationName を特定できない場合<see cref="T:System.Fabric.CodePackageActivationContext" />です。
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetFabricServiceUri">
      <MemberSignature Language="C#" Value="public static Uri GetFabricServiceUri (Type actorInterfaceType, Uri applicationUri, string serviceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Uri GetFabricServiceUri(class System.Type actorInterfaceType, class System.Uri applicationUri, string serviceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetFabricServiceUri(System.Type,System.Uri,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetFabricServiceUri (actorInterfaceType As Type, applicationUri As Uri, serviceName As String) As Uri" />
      <MemberSignature Language="F#" Value="static member GetFabricServiceUri : Type * Uri * string -&gt; Uri" Usage="Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetFabricServiceUri (actorInterfaceType, applicationUri, serviceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="actorInterfaceType" Type="System.Type" />
        <Parameter Name="applicationUri" Type="System.Uri" />
        <Parameter Name="serviceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="actorInterfaceType">アクター インターフェイスの型。</param>
        <param name="applicationUri">Service Fabric アプリケーション アクター サービスを含む Uri です。
            アプリケーション名がから取得した場合、この値は null<see cref="P:System.Fabric.CodePackageActivationContext.ApplicationName" />です。</param>
        <param name="serviceName">アクターの種類をホストするサービスの名前です。 この値が null の場合サービス名は、使用して、actorInterfaceType で作成されます。</param>
        <summary>
            サービスの Service Fabric クラスター内のアクターの種類をホストする Uri を取得します。
            </summary>
        <returns>Service Fabric サービスのアクターの種類をホストしている Uri。</returns>
        <remarks>アプリケーション名を取得しようとは applicationUri が null として渡されると場合、<see cref="T:System.Fabric.CodePackageActivationContext" />です。 メソッドはまだアプリケーション名を判別できない場合<see cref="T:System.ArgumentException" />がスローされます。 </remarks>
        <exception cref="T:System.ArgumentException">
            使用してアプリケーションの名前を特定できない場合<see cref="T:System.Fabric.CodePackageActivationContext" />です。
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetFabricServiceV2EndpointName">
      <MemberSignature Language="C#" Value="public static string GetFabricServiceV2EndpointName (Type actorImplementationType);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GetFabricServiceV2EndpointName(class System.Type actorImplementationType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetFabricServiceV2EndpointName(System.Type)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetFabricServiceV2EndpointName (actorImplementationType As Type) As String" />
      <MemberSignature Language="F#" Value="static member GetFabricServiceV2EndpointName : Type -&gt; string" Usage="Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetFabricServiceV2EndpointName actorImplementationType" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="actorImplementationType" Type="System.Type" />
      </Parameters>
      <Docs>
        <param name="actorImplementationType">アクターを実装するクラスの型。</param>
        <summary>
            アクター サービスのサービス マニフェストに指定されているアクターの種類のサービス エンドポイントを取得します。
            </summary>
        <returns>サービス エンドポイントの名前。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetLocalEseStoreConfigSectionName">
      <MemberSignature Language="C#" Value="public static string GetLocalEseStoreConfigSectionName (Type actorImplementationType);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GetLocalEseStoreConfigSectionName(class System.Type actorImplementationType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetLocalEseStoreConfigSectionName(System.Type)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetLocalEseStoreConfigSectionName (actorImplementationType As Type) As String" />
      <MemberSignature Language="F#" Value="static member GetLocalEseStoreConfigSectionName : Type -&gt; string" Usage="Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetLocalEseStoreConfigSectionName actorImplementationType" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="actorImplementationType" Type="System.Type" />
      </Parameters>
      <Docs>
        <param name="actorImplementationType">アクターを実装するクラスの型。</param>
        <summary>
            アクター サービス用の構成パッケージで指定されたローカル ストアの構成セクション名を取得します。 
            </summary>
        <returns>ローカル ストアの構成セクション名。</returns>
        <remarks>ローカルの ESE 構成セクションで指定された値を使用して構成<see cref="T:System.Fabric.LocalEseStoreSettings" />アクターの状態を格納するためです。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetName">
      <MemberSignature Language="C#" Value="public static string GetName (Type actorInterfaceType);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GetName(class System.Type actorInterfaceType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetName(System.Type)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetName (actorInterfaceType As Type) As String" />
      <MemberSignature Language="F#" Value="static member GetName : Type -&gt; string" Usage="Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetName actorInterfaceType" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="actorInterfaceType" Type="System.Type" />
      </Parameters>
      <Docs>
        <param name="actorInterfaceType">アクター インターフェイスの型。</param>
        <summary>
            ActorInterfaceType からアクターの名前を取得します。
            </summary>
        <returns>アクターの名前です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>