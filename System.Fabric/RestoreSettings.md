<Type Name="RestoreSettings" FullName="System.Fabric.RestoreSettings">
  <TypeSignature Language="C#" Value="public sealed class RestoreSettings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit RestoreSettings extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.RestoreSettings" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class RestoreSettings" />
  <TypeSignature Language="F#" Value="type RestoreSettings = class" />
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
            キー/値のストアの設定を表します<see cref="M:System.Fabric.KeyValueStoreReplica.RestoreAsync(System.String,System.Fabric.RestoreSettings,System.Threading.CancellationToken)" />操作します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RestoreSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.RestoreSettings.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <see cref="T:System.Fabric.RestoreSettings" /> クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RestoreSettings (bool inlineReopen);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(bool inlineReopen) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.RestoreSettings.#ctor(System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (inlineReopen As Boolean)" />
      <MemberSignature Language="F#" Value="new System.Fabric.RestoreSettings : bool -&gt; System.Fabric.RestoreSettings" Usage="new System.Fabric.RestoreSettings inlineReopen" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="inlineReopen" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="inlineReopen">
            示す場合、<see cref="T:System.Fabric.KeyValueStoreReplica" />を再度開いて自体が正常に指定されたバックアップから復元した後です。 False が指定されている場合、レプリカは、修復が成功した後に一時的なエラーを報告します。 
            </param>
        <summary>
            <see cref="T:System.Fabric.RestoreSettings" /> クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RestoreSettings (bool inlineReopen, bool enableLsnCheck);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(bool inlineReopen, bool enableLsnCheck) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.RestoreSettings.#ctor(System.Boolean,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (inlineReopen As Boolean, enableLsnCheck As Boolean)" />
      <MemberSignature Language="F#" Value="new System.Fabric.RestoreSettings : bool * bool -&gt; System.Fabric.RestoreSettings" Usage="new System.Fabric.RestoreSettings (inlineReopen, enableLsnCheck)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="inlineReopen" Type="System.Boolean" />
        <Parameter Name="enableLsnCheck" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="inlineReopen">
            示す場合、<see cref="T:System.Fabric.KeyValueStoreReplica" />を再度開いて自体が正常に指定されたバックアップから復元した後です。 False が指定されている場合、レプリカは、修復が成功した後に一時的なエラーを報告します。  
            </param>
        <param name="enableLsnCheck">
            示す場合、<see cref="T:System.Fabric.KeyValueStoreReplica" />ことを確認する必要があります  
            復元データがデータ サービスに現在存在よりも古いではありません。
            これは、偶発的なデータ損失から保護されます。 場合は false を指定すると、<see cref="T:System.Fabric.KeyValueStoreReplica" />場合でも、データをサービスに提示は、現在のサービス データを復元データで上書きは新しいです。 
            </param>
        <summary>
            <see cref="T:System.Fabric.RestoreSettings" /> クラスの新しいインスタンスを初期化します。 
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableLsnCheck">
      <MemberSignature Language="C#" Value="public bool EnableLsnCheck { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool EnableLsnCheck" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.RestoreSettings.EnableLsnCheck" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EnableLsnCheck As Boolean" />
      <MemberSignature Language="F#" Value="member this.EnableLsnCheck : bool" Usage="System.Fabric.RestoreSettings.EnableLsnCheck" />
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
            示す場合、<see cref="T:System.Fabric.KeyValueStoreReplica" />ことを確認する必要があります  
            復元データがデータ サービスに現在存在よりも古いではありません。
            これは、偶発的なデータ損失から保護されます。 場合は false を指定すると、<see cref="T:System.Fabric.KeyValueStoreReplica" />場合でも、データをサービスに提示は、現在のサービス データを復元データで上書きは新しいです。 
            </summary>
        <value>
            A<see cref="T:System.Boolean" />値どうかを示す<see cref="T:System.Fabric.KeyValueStoreReplica" />復元データがデータ サービスに現在存在よりも古くないかどうかは確認します。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InlineReopen">
      <MemberSignature Language="C#" Value="public bool InlineReopen { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool InlineReopen" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.RestoreSettings.InlineReopen" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property InlineReopen As Boolean" />
      <MemberSignature Language="F#" Value="member this.InlineReopen : bool" Usage="System.Fabric.RestoreSettings.InlineReopen" />
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
            示す場合、<see cref="T:System.Fabric.KeyValueStoreReplica" />を再度開いて自体が正常に指定されたバックアップから復元した後です。 False が指定されている場合、レプリカは、修復が成功した後に一時的なエラーを報告します。 
            </summary>
        <value>
            A<see cref="T:System.Boolean" />値どうかを示す<see cref="T:System.Fabric.KeyValueStoreReplica" />が再び開く自体の復元後にします。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>