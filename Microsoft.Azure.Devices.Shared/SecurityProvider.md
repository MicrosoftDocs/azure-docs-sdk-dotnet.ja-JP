<Type Name="SecurityProvider" FullName="Microsoft.Azure.Devices.Shared.SecurityProvider">
  <TypeSignature Language="C#" Value="public abstract class SecurityProvider : IDisposable" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit SecurityProvider extends System.Object implements class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Devices.Shared.SecurityProvider" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class SecurityProvider&#xA;Implements IDisposable" />
  <TypeSignature Language="F#" Value="type SecurityProvider = class&#xA;    interface IDisposable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Devices.Shared</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            セキュリティが使用するプロバイダー ProvisioningDeviceClient 認証します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected SecurityProvider ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Shared.SecurityProvider.#ctor" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Shared</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Dispose">
      <MemberSignature Language="C#" Value="public void Dispose ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Dispose() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Shared.SecurityProvider.Dispose" />
      <MemberSignature Language="VB.NET" Value="Public Sub Dispose ()" />
      <MemberSignature Language="F#" Value="abstract member Dispose : unit -&gt; unit&#xA;override this.Dispose : unit -&gt; unit" Usage="securityProvider.Dispose " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.IDisposable.Dispose</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Shared</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            呼び出し元が使っているアンマネージ リソースを解放し、マネージ リソースを破棄します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Dispose">
      <MemberSignature Language="C#" Value="protected abstract void Dispose (bool disposing);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void Dispose(bool disposing) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Shared.SecurityProvider.Dispose(System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Sub Dispose (disposing As Boolean)" />
      <MemberSignature Language="F#" Value="abstract member Dispose : bool -&gt; unit" Usage="securityProvider.Dispose disposing" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Shared</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="disposing" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="disposing">マネージ コードとアンマネージ リソースを解放する場合は truefalse には、アンマネージ リソースだけを解放します。</param>
        <summary>
            SecurityProvider によって使用されているアンマネージ リソースを解放し、必要に応じてマネージ リソースを破棄します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRegistrationID">
      <MemberSignature Language="C#" Value="public abstract string GetRegistrationID ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance string GetRegistrationID() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Shared.SecurityProvider.GetRegistrationID" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function GetRegistrationID () As String" />
      <MemberSignature Language="F#" Value="abstract member GetRegistrationID : unit -&gt; string" Usage="securityProvider.GetRegistrationID " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Shared</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            デバイスの登録時に使用される登録 ID を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>