<Type Name="ConfigurationProperty" FullName="System.Fabric.Description.ConfigurationProperty">
  <TypeSignature Language="C#" Value="public sealed class ConfigurationProperty" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ConfigurationProperty extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.ConfigurationProperty" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ConfigurationProperty" />
  <TypeSignature Language="F#" Value="type ConfigurationProperty = class" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para>構成設定と、サービスまたはアプリケーション構成に使用できる値を指定します。</para>
      <para>設定は、サービス マニフェスト内の settings.xml ファイルに指定します。 詳細については、https://docs.microsoft.com/azure/service-fabric/service-fabric-application-model を参照してください。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DecryptValue">
      <MemberSignature Language="C#" Value="public System.Security.SecureString DecryptValue ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Security.SecureString DecryptValue() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ConfigurationProperty.DecryptValue" />
      <MemberSignature Language="VB.NET" Value="Public Function DecryptValue () As SecureString" />
      <MemberSignature Language="F#" Value="member this.DecryptValue : unit -&gt; System.Security.SecureString" Usage="configurationProperty.DecryptValue " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Security.SecureString</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para>暗号化された値を復号化し、SecureString として返します。</para>
        </summary>
        <returns>
          <para><see cref="T:System.Security.SecureString" /> を返します。</para>
        </returns>
        <remarks>Https://docs.microsoft.com/azure/service-fabric/service-fabric-application-secret-management メソッドを使用してこの値は実行時の暗号化を解除する方法と、シークレットを暗号化し、構成に格納する方法の例についてを参照してください。</remarks>
        <exception cref="T:System.InvalidOperationException">
          <para>値、<see cref="T:System.Fabric.Description.ConfigurationProperty" />は暗号化されません。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="IsEncrypted">
      <MemberSignature Language="C#" Value="public bool IsEncrypted { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsEncrypted" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ConfigurationProperty.IsEncrypted" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsEncrypted As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsEncrypted : bool" Usage="System.Fabric.Description.ConfigurationProperty.IsEncrypted" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>構成が暗号化されているかどうかを示すフラグを取得します。 </para>
        </summary>
        <value>
          <para>構成が暗号化されている; 場合、true を返しますfalse の場合、それ以外の場合。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MustOverride">
      <MemberSignature Language="C#" Value="public bool MustOverride { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool MustOverride" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ConfigurationProperty.MustOverride" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MustOverride As Boolean" />
      <MemberSignature Language="F#" Value="member this.MustOverride : bool" Usage="System.Fabric.Description.ConfigurationProperty.MustOverride" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>アプリケーション マニフェストに、設定をオーバーライドする必要があるかどうかを示すフラグを取得します。</para>
        </summary>
        <value>
          <para>アプリケーション マニフェストに、設定をオーバーライドする必要があるかどうかを示すフラグします。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ConfigurationProperty.Name" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string" Usage="System.Fabric.Description.ConfigurationProperty.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>サービス マニフェスト内の settings.xml ファイルに指定された設定の名前を取得します。</para>
        </summary>
        <value>
          <para>設定の名前。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Value">
      <MemberSignature Language="C#" Value="public string Value { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Value" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ConfigurationProperty.Value" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Value As String" />
      <MemberSignature Language="F#" Value="member this.Value : string" Usage="System.Fabric.Description.ConfigurationProperty.Value" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>設定の値を取得します。</para>
        </summary>
        <value>
          <para>設定の値です。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>