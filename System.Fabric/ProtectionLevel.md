<Type Name="ProtectionLevel" FullName="System.Fabric.ProtectionLevel">
  <TypeSignature Language="C#" Value="public enum ProtectionLevel" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed ProtectionLevel extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.ProtectionLevel" />
  <TypeSignature Language="VB.NET" Value="Public Enum ProtectionLevel" />
  <TypeSignature Language="F#" Value="type ProtectionLevel = " />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
      <para><span data-ttu-id="516fe-101">通信を保護する方法を列挙します。</span><span class="sxs-lookup"><span data-stu-id="516fe-101">Enumerates how communication is protected.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="EncryptAndSign">
      <MemberSignature Language="C#" Value="EncryptAndSign" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.ProtectionLevel EncryptAndSign = int32(2)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.ProtectionLevel.EncryptAndSign" />
      <MemberSignature Language="VB.NET" Value="EncryptAndSign" />
      <MemberSignature Language="F#" Value="EncryptAndSign = 2" Usage="System.Fabric.ProtectionLevel.EncryptAndSign" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ProtectionLevel</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="516fe-102">機密性と整合性が保護されます。</span><span class="sxs-lookup"><span data-stu-id="516fe-102">Both confidentiality and integrity are protected.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="None">
      <MemberSignature Language="C#" Value="None" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.ProtectionLevel None = int32(0)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.ProtectionLevel.None" />
      <MemberSignature Language="VB.NET" Value="None" />
      <MemberSignature Language="F#" Value="None = 0" Usage="System.Fabric.ProtectionLevel.None" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ProtectionLevel</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="516fe-103">保護されていません。</span><span class="sxs-lookup"><span data-stu-id="516fe-103">Not protected.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Sign">
      <MemberSignature Language="C#" Value="Sign" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.ProtectionLevel Sign = int32(1)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.ProtectionLevel.Sign" />
      <MemberSignature Language="VB.NET" Value="Sign" />
      <MemberSignature Language="F#" Value="Sign = 1" Usage="System.Fabric.ProtectionLevel.Sign" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ProtectionLevel</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="516fe-104">整合性のみが保護されています。</span><span class="sxs-lookup"><span data-stu-id="516fe-104">Only integrity is protected.</span></span></para>
        </summary>
      </Docs>
    </Member>
  </Members>
</Type>